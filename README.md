# HONINA - infobot demo
Honina is an infobot demo with NLP and TTS capabilities (like Alexa).

### Run and Usage
Just run the **honina.py** file with ```python honina.py``` in the shell prompt. Right after Honina will welcome you. After that you can say hi via command shell or ask her for the weather, room .. etc. 

language support: **German**

intents: Wetter, Raumsuche

### Dependencies
Install the following packages.

api.ai python api (NLP):
```
pip install apiai
```
google text to speech (tts):
```
sudo pip install gTTS
```
lightweight mp3 player:
```
sudo apt-get install mpg321
```
JSON client:
```
pip install simplejson
```

### Links
* [psdk ](https://github.com/api-ai/api-ai-python) - api.ai python sdk
* [apiai_model ](https://console.api.ai/) - api.ai edit NLP model
