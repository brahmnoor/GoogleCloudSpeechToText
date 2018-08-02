# Google Cloud Speech-to-Text based on NodeJS and SocketIO for Real Time Detection
This is a project based on NodeJS and SocketIO for real-time detection of speech to text. This supports all the languages in Google Cloud Speech API including Cantonese and Chinese.

## Setup
- Place the authentication file (auth.json) in the root folder (get it from Google Cloud Speech API dashboard). 
- Run npm install (again on the root folder) to install the dependencies. 
- Run node app.js, and navigate to http://127.0.0.1:1337/, to run the script.

## Main File Structure
- app.js - Express based script for sever-side stuff.
- client.js - Client-side script, handling the audio context, getting the audio buffer, converting it to a format suitable for Google Cloud API and sending it back using SocketIO.
