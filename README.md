# SimpleGPT
# Introduction

SimpleGPT is an interactive Python application that integrates OpenAI's GPT models with text-to-speech and speech recognition capabilities. It provides a unique conversational experience with an AI that simulates emotions and responds with a human-like understanding. The script uses OpenAI's GPT-3.5-turbo model by default, with the option to switch to GPT-4.
Features

    Interactive AI Conversation: Engage in conversations with an AI that can simulate emotional responses, making the interaction more engaging and realistic.
    Voice Interaction: Utilizes text-to-speech and speech recognition for a hands-free conversational experience.
    Model Flexibility: Choose between GPT-3.5-turbo and GPT-4 models for conversation.
    Customizable AI Persona: Ability to customize the AI persona through a text file or default settings.
    Voice Selection: Offers the choice between different voice types for text-to-speech output.

Requirements

    Python 3.x
    OpenAI Python library
    win32com.client for text-to-speech
    speech_recognition and pyaudio for speech recognition

Setup and Installation

    Ensure Python 3.x is installed.
    Install the necessary Python libraries:

    pip install openai pywin32 SpeechRecognition pyaudio

    Set your OPENAI_API_KEY in your environment variables.

Usage

Run the script in a Python environment and follow the on-screen prompts to select the GPT model and interaction mode.

python SimpleGPT.py

Choose between text-to-text, text-to-voice, or voice-to-voice interaction modes and start conversing with SimpleGPT.
Contribution

Contributions to SimpleGPT are welcome. Feel free to fork the repository, make improvements, and open pull requests. For major changes or suggestions, please open an issue first to discuss what you would like to change.
License

This project is released under the MIT License.
Disclaimer

This project is not officially associated with OpenAI. It is developed for educational purposes and personal interest in AI and speech interaction technologies.
