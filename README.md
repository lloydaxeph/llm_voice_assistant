# Gemini AI voice assitant

## 1.0 About
This project aims to demonstrate how to create a simple AI voice assistant that can help you with your daily queries.
This AI assistant can transcribe audio into text and turn text into audio.

The demo application will be made using [streamlit](https://streamlit.io/). The brains for this AI assistant if Google's [Gemini](https://gemini.google.com/). 
The ears would be [audio_recorder_streamlit](https://pypi.org/project/audio-recorder-streamlit/) and the voice will be from [pyttsx3](https://pypi.org/project/pyttsx3/).


## 2.0 Getting Started
### 2.1 Installation
Install the required packages.
```
pip3 install -r requirements.txt
```
### 2.2 Create an API key
This project requires you to have your own **Google AI Studio API key**. To learn how to create your own API Key, please check [Google AI Studio - Get API key](https://aistudio.google.com/app/apikey). 
Once you have the API Key, use it to configure `google.generativeai`.
```
genai.configure(api_key='{YOUR_GOOGLE_GEMINI_API}')
```

### 2.3 Run App
To run the app, simply input the following command to your terminal:
```
streamlit run app.py
```

### 2.4 Customize Model Configurations
The configurations for this model can be found in [configs.py](configs.py). You can modify the existing parameter to your liking.
