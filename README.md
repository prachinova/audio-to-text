
##  Audio-to-Text Transcription Script
This script uses voice recognition to capture spoken input, converts it to text, and outputs the recognized command. It’s designed as a foundational module for applications that require voice-to-text capabilities.

## Features
Real-Time Voice Input: Captures audio input from the microphone.

Speech-to-Text Conversion: Uses Google’s Speech Recognition API to transcribe audio.

Error Handling: Detects and informs of errors when speech input isn’t recognized.

##  Requirements
Python 3.6+
## Required Libraries:
speech_recognition

pyaudio

pyttsx3 (for audio feedback)

## Install the dependencies with:
*pip install speechrecognition pyaudio pyttsx3*
## Run the Script:
python audio_to_text.py
##  Give Voice Input: Speak into the microphone; the script will output the recognized text.

**Example Command**
After starting the script, say something like:

"Create a button labeled 'Submit'."

The script will transcribe this and display:

Command recognized: Create a button labeled 'Submit'.


##  Notes
Microphone Access: Ensure your device has a working microphone.

API Usage: This script uses Google’s free, online speech recognition API.
