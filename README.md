# Voice Assistant

## Overview
This project is a simple voice assistant built using Python. It leverages various libraries and APIs to perform tasks such as answering questions, fetching weather updates, sending emails, playing music, and more, all through voice commands.

## Key Features
- **Voice Recognition:** The assistant listens for voice commands using the SpeechRecognition library.
- **Text-to-Speech:** Responses are generated using the pyttsx3 library, allowing the assistant to speak to the user.
- **Task Automation:** It can perform various tasks such as fetching information from Wikipedia, checking the weather, playing music, sending emails, and more.
- **Personalization:** Users can customize the assistant's name and interact with it in a conversational manner.
- **Weather Updates:** The assistant can provide real-time weather updates for any location using the OpenWeatherMap API.
- **News Feeds:** Users can get the latest news headlines from various sources using the BBC News RSS feed.
- **Email Sending:** The assistant can send emails to specified recipients using the smtplib library.

## Usage
1. Run the `main.py` script to start the voice assistant.
2. Upon startup, the assistant will greet the user and ask for their name.
3. Speak commands such as "Jarvis, what's the weather like today?" or "Jarvis, play some music" to interact with the assistant.
4. The assistant will respond to commands and perform the requested actions.

## Requirements
Ensure you have the following dependencies installed:
- wolframalpha==5.0.0
- pyttsx3==2.90
- SpeechRecognition==3.8.1
- wikipedia==1.4.0
- feedparser==6.0.8
- twilio==6.68.0
- beautifulsoup4==4.10.0
- requests==2.26.0
- pyjokes==0.6.0

You can install them using `pip install -r requirements.txt`.

## Contributing
Contributions are welcome! If you have any suggestions or would like to improve the project, feel free to do so.
