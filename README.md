# LANGUAGE-TRANSLATOR-APP

## Overview

The **Language Translation App** is a web application that allows users to translate text from one language to another, with an added feature of audio output for the translated text. The app uses **Streamlit** for the frontend, **mtranslate** for text translation, **gTTS (Google Text-to-Speech)** for generating audio, and **base64** for encoding the audio file, allowing users to download it. This app is perfect for multilingual communication, travel assistance, and language learning.

## Features

- **Real-Time Language Translation**: Translate input text to the selected target language.
- **Audio Output**: Listen to the translated text through an audio file to assist with pronunciation.
- **User-Friendly Interface**: Intuitive and simple interface built with Streamlit.
- **Downloadable Audio File**: Option to download the audio file of the translated text for offline use.

## Technologies Used

- **Streamlit**: For building the interactive web interface.
- **mtranslate**: For translating text between multiple languages.
- **gTTS (Google Text-to-Speech)**: Converts text to speech for audio output.
- **base64**: Encodes the audio file for playback and download within the app.
- **pandas**: (Optional) Used for data manipulation if required.
- **os**: Provides functionality to interact with the operating system.

## Usage

1. Open the app in your browser.
2. Enter the text you want to translate in the **Write Your Text** field.
3. Select the target language from the **Select Language to Translate** dropdown menu.
4. Click the **Convert** button to generate the translation and audio.
5. The **Translated Text** will appear below, along with an audio player to listen to the translation.
6. You can download the audio file by clicking the **Download Audio File** link.

## Project Structure

- **app.py**: Main application file that contains the Streamlit app code.
- **requirements.txt**: List of required libraries.
- **README.md**: Documentation file.

## Screenshot

![Screenshot (1793)](https://github.com/user-attachments/assets/72c3e8fa-9066-4d07-982d-0924ee7d4f7c)

## Conclusion

The **Language Translation App** provides an easy and effective solution for real-time text translation with audio output. Whether for overcoming language barriers in communication, assisting travelers, or supporting language learners, this app simplifies multilingual interactions. With its straightforward interface and convenient features, it’s a valuable tool for language accessibility and global communication.
