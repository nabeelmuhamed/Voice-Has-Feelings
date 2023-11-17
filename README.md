<h1>Audio-to-Text and Sentiment Analysis Program Documentation</h1><br>

<h3>Overview</h3>

  
This document provides information on how to use a Python program for converting audio from an MP3 file to text and then performing sentiment analysis on the transcribed text. The program utilizes the SpeechRecognition library for audio-to-text conversion and the TextBlob library for sentiment analysis.

<h4>Prerequisites</h4>
Before using the program, make sure to install the required Python libraries using the following commands:

----pip install SpeechRecognition<br>
----pip install textblob<br><br>

<h3>Usage</h3>

--**Download the Program**:

Download the Python script (audio_to_text_sentiment_analysis.py) provided in this repository.

--**Install Dependencies**:

Ensure that you have Python installed on your machine.
Open a terminal and install the required libraries using the commands mentioned in the "Prerequisites" section.<br>

--**Run the Program**:

Open a terminal and navigate to the directory containing the script.

Execute the script using the following command:**python audio_to_text_sentiment_analysis.py**

--**Input MP3 File**:

When prompted, provide the path to the MP3 file you want to analyze.
Example: path/to/your/file.mp3

--**View Results**:

The program will transcribe the audio to text using Google Speech Recognition and display the transcribed text.<br>
It will then perform sentiment analysis on the transcribed text and print the sentiment (Positive, Negative, or Neutral).


<h3>Notes</h3>
--If the audio file contains complex language, background noise, or multiple speakers, the accuracy of the transcription may vary.<br>
--The sentiment analysis is based on a basic polarity analysis using the TextBlob library. More advanced sentiment analysis models may provide better accuracy.
