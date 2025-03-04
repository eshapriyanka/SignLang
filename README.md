# SignLang
## Automatic Indian Sign Language Translator (ISL) ##

This application translates spoken words into Indian Sign Language (ISL) representations using a dictionary-based approach. It captures speech through a microphone, converts it into text, and displays corresponding ISL images or GIFs if available. If a direct ISL translation is not found, it displays letter-by-letter finger-spelling images.

Speech to Text conversion using Google Speech API.
Dictionary-based ISL translation for predefined words and phrases.
Letter-by-letter representation for words without a direct ISL translation.
GIF-based sign representation for commonly used phrases.
Easy-to-use graphical interface with EasyGUI.
Exit command: Say "goodbye" or "bye" to stop the program.

## Technologies used
Python (Core Language)
PyAudio (Capturing Speech)
SpeechRecognition (Google Speech API)
EasyGUI (User Interface)
Tkinter (Displaying GIFs)
Matplotlib & PIL (Displaying Images)
Project Structure
graphql

## How It Works
1. Speech Input
  The application listens for speech using a microphone.
  Background noise is adjusted for better recognition.
2. Speech-to-Text Conversion
  Converts speech to text using Google Speech API.
  Punctuation is removed for uniformity.
3. ISL Translation
  If the spoken phrase exists in the predefined dictionary, the corresponding GIF is displayed.
  If the phrase is not found, each letter of the word is displayed using alphabet sign images.
4. User Interaction
  The program starts with a GUI menu.
  Click "Live Voice" to start speech recognition.
  The translated ISL GIF or images appear accordingly.
  Say "goodbye" to exit the program.

## Installation & Usage
1. Install Dependencies
  Ensure you have Python installed, then run:
  pip install pyaudio speechrecognition easygui matplotlib pillow
2. Run the Application
  python main.py
3. Use the Interface
  Click "Live Voice" to start capturing speech.
  View the translated Indian Sign Language visuals.
  Say "bye" or "goodbye" to exit the application.
