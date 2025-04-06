# 🕑 Azure AI Services Speaking Clock (Python)
A hands-on project using Azure AI Speech Services and Python to build a speaking clock app! 🎤🕰️

# 📚 Project Overview
In this project, you'll learn how to:

✅ Create an Azure AI Speech resource

✅ Build a Python app to recognize speech and announce the time

✅ Use the Azure SDK for speech-to-text and text-to-speech

✅ Run locally using your microphone or an audio file

✅ Clean up Azure resources after use

# 🛠️ Tech Stack
```bash 
Python 3.10+

Azure AI Speech Services

Azure SDK for Python

VS Code (recommended)
```

# 🧩 How to Run Locally

## 🚀 1. Clone the Repository
```bash
git clone https://github.com/MouryaSagar17/Azure-AI-Services-Speaking-Clock.git
cd speech/Python/speaking-clock
```
## ⚙️ 2. Set Up Environment Variables
Create a .env file in the speaking-clock folder:

```env
SPEECH_KEY=your-speech-key-here
SPEECH_REGION=your-region-here  # Example: eastus
```
## 📦 3. Install Dependencies
```bash
pip install azure-cognitiveservices-speech==1.30.0 playsound==1.2.2
```
## 🏃 4. Run the App
```bash

python speaking-clock.py
```
## 🎙️ Speak clearly into your mic and ask:

"What time is it?"

The app will recognize your speech and respond with the current time using AI-powered voice synthesis! 🗣️✨

## 🎯 Features
```bash
🎤 Speech recognition (microphone or audio file)

🕰️ Announces the current time

🧠 Powered by Azure Speech-to-Text and Text-to-Speech

🎛️ Supports customizable voices (e.g., en-GB-RyanNeural)

🔐 Secure with API keys via environment variables

🖥️ Lightweight and console-based for quick testing
```
# 🧹 Clean Up
To avoid charges, delete your Azure resources after testing:

Go to the Azure Portal

Delete the resource group created for this project

# 📖 Learn More
Azure AI Speech Services Documentation

Azure Speech SDK for Python

# 🌟 Acknowledgements
Huge thanks to Microsoft Learn for providing the base structure and learning materials! 🙌

# 🚀 Final Note
This project gave me real-world experience integrating Python apps with Azure AI—fast, efficient, and super fun! Can’t wait to build even more voice-powered apps! 🎤💬✨

