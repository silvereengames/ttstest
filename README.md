# Text To Speech Utility
A simple TTS tool to implament into all your Javascript web pages.

### Install
Download the script and refrence it for example: ```<script src="ttstool.js"></script>```
or
Just use the Github raw content and no downloaded is needed: ```https://raw.githubusercontent.com/silvereengames/ttsutility/main/main.js```

### Use
To be honest I just pulled all the code and API from responsivevoice.org so credits to them
Speak something: ```responsiveVoice.speak("hello world");```
Speak something in a different voice: ```responsiveVoice.speak("hello world", "UK English Male");``` (voices are from Google voices)
Change the pitch: ```responsiveVoice.speak("hello world", "UK English Male", {pitch: 2});```
Change the speak rate: ```responsiveVoice.speak("hello world", "UK English Male", {rate: 1.5});```
Change the volume: ```responsiveVoice.speak("hello world", "UK English Male", {volume: 1});```
Speak a element on a page: ```responsiveVoice.speak(document.getElementById("article-container").textContent);```
Stop speaking: ```responsiveVoice.cancel();```
Their is more documentation on https://responsivevoice.org/api/

### Credits
Like I said this code and API is NOT mine and I copied from https://responsivevoice.org/ so all credit goes to them. This repo was created so you don't have to create an account and to have custom code in the case you need it.


