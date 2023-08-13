# Desktop Assitant 🤖

This is an interactive voice-activated personal assistant powered by OpenAI's GPT-4 model. It can converse with users, open specific websites, play music, provide the current time, and much more.

## 🚀 Features

- **🎙️ Voice Recognition**: Recognizes voice commands and executes them.
- **💬 Dynamic OpenAI Conversations**: Uses the GPT-4 model to engage in dynamic conversations.
- **🌐 Web Browser Integration**: Opens popular sites like YouTube, Wikipedia, and Google with a simple voice command.
- **📁 File Management**: Automatically saves OpenAI responses in neatly organized text files.
- **🖥️ System Commands**: Engages with native apps like FaceTime, plays music, and more.

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Required Python libraries:
  - `speech_recognition`
  - `web browser`
  - `openai`
  - `numpy`
  - `datetime`
  - `random`

You can install these with pip: <br>
`pip install -r requirements.txt`


> **Note**: Store your OpenAI API key in a `config.py` file under the variable `apikey`.

## 🛠️ Setup & Running

1. Clone this repository: <br>
`git clone LINK_TO_YOUR_REPOSITORY`

2. Navigate to the project directory: <br>
`cd DIRECTORY_NAME`

3. Run Jarvis:<br>
`python main.py`


4. Start conversing with Jarvis by speaking into your microphone!

## 🗣️ Commands Guide

- **Open Websites**: "Open [website_name]" - Supported sites: YouTube, Wikipedia, Google.
- **Music**: "Open music" - Plays a preset music track.
- **Time**: "What's the time?" - Provides the current time.
- **FaceTime**: "Open FaceTime" - Launches the FaceTime app.
- **OpenAI Queries**: "Using artificial intelligence [QUERY]" - Retrieves and saves a response from OpenAI.
- **Exit**: "Jarvis Quit" - Exits the application.
- **Reset**: "Reset chat" - Resets the conversation string.

## ⚠️ Caution

Please handle the OpenAI API key with utmost care. Avoid exposing it publicly.
