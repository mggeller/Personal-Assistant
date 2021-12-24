# Personal-Assistant

##Installation

For Personal Assistant to work, you need to install the Python virtual environemnt in the folder using this command:

```bash
python -m venv env
```

After that Environemnt needs to be activated using this command:

(Linux/Mac)
```bash
. env/Scripts/activate
```

or 

(Windows)
```bash
Personal-Assistant/Scripts/activate
```

To verify if the environment has been activated or not, you can see (env) in your terminal

After that, it is needed to install all the libraries used in the project:

```bash
pip install pyttsx3

pip install SpeechRecognition

pip install pywhatkit

pip install wikipedia

pip install requests

pip install python-decouple
```

You also might need to install PyAudio for this project. You can do this with these commands for example:
```bash
pip install pipwin

pipwin install pyaudio
```

## Usage

To use this you have to activate the Virtual Environemnt and also create and add correct values in the .env file.
Example of the keys taht should be in the .env file:

USER=<Your name>
BOTNAME=<Whatever you want this asstistants name to be>
NEWS_API_KEY=<[News API key](https://newsapi.org/)>
OPENWEATHER_APP_ID=<[Weather API Key](https://openweathermap.org/)>
TMDB_API_KEY=<[Movie API Key](https://www.themoviedb.org/)>
EMAIL=<Your email>
PASSWORD=<Your email password>

Tutorials and more in depth information how to start can be found here - https://iread.ga/series/10/virtual-personal-assistant-using-python
