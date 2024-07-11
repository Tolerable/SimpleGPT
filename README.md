# SIMPLEGPT

SIMPLEGPT is an interactive AI companion built using the OpenAI API and text-to-speech technologies. This project allows users to select different models and personas for their AI companion and interact with it via text or voice.

## Features

- Choose between GPT-3.5-turbo, GPT-4-turbo, and GPT-4o models.
- Select from predefined personas or load a custom persona from a file.
- Interact with the AI via text-to-text, text-to-voice, or voice-to-voice modes.
- Automatic handling and sanitization of AI responses for compatibility with text-to-speech.

## Requirements

- Python 3.x
- `win32com.client` for text-to-speech
- `speech_recognition` for voice input
- `pyaudio` for microphone access
- `openai` for accessing the GPT models

## Setup

1. Install the required packages:
    ```sh
    pip install pywin32 SpeechRecognition pyaudio openai
    ```

2. Set your OpenAI API key as an environment variable:
    ```sh
    export OPENAI_API_KEY='your-api-key-here'
    ```

3. Run the script:
    ```sh
    python SIMPLEGPT.py
    ```

## Usage

1. Follow the prompts to select the GPT model, persona, voice, and interaction mode.
2. Interact with the AI companion according to the selected mode.
3. Type "exit" to quit the interaction at any time.

## Files# SIMPLEGPT

SIMPLEGPT is an interactive AI companion built using the OpenAI API and text-to-speech technologies. This project allows users to select different models and personas for their AI companion and interact with it via text or voice.

## Features

- Choose between GPT-3.5-turbo, GPT-4-turbo, and GPT-4o models.
- Select from predefined personas or load a custom persona from a file.
- Interact with the AI via text-to-text, text-to-voice, or voice-to-voice modes.
- Automatic handling and sanitization of AI responses for compatibility with text-to-speech.

## Requirements

- Python 3.x
- `win32com.client` for text-to-speech
- `speech_recognition` for voice input
- `pyaudio` for microphone access
- `openai` for accessing the GPT models

## Setup

1. Install the required packages:
    ```sh
    pip install pywin32 SpeechRecognition pyaudio openai
    ```

2. Set your OpenAI API key as an environment variable:
    ```sh
    export OPENAI_API_KEY='your-api-key-here'
    ```

3. Run the script:
    ```sh
    python SIMPLEGPT.py
    ```

## Usage

1. Follow the prompts to select the GPT model, persona, voice, and interaction mode.
2. Interact with the AI companion according to the selected mode.
3. Type "exit" to quit the interaction at any time.

## Files

- `SIMPLEGPT.py`: Main script to run the AI companion.
- `README.md`: This readme file.
- `LICENSE`: License information.
- `.gitignore`: Git ignore file to exclude unnecessary files from the repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.


- `SIMPLEGPT.py`: Main script to run the AI companion.
- `README.md`: This readme file.
- `LICENSE`: License information.
- `.gitignore`: Git ignore file to exclude unnecessary files from the repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
