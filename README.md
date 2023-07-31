# Text Translator and Text-to-Speech App

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description

The Text Translator and Text-to-Speech App is a Flask-based web application that allows users to translate text into various languages using the Google Translate API. Additionally, the app can convert the translated text into speech using the gTTS (Google Text-to-Speech) library.

## Features

- Text Translation: Users can enter a sentence and choose a target language from a list of supported languages. The app will then translate the sentence into the selected language using the Google Translate API.
- Text-to-Speech: The app can convert the translated text into speech and play it back to the user as an MP3 audio file.
- User-Friendly Interface: The web interface is simple and intuitive, making it easy for users to interact with the app and perform translations.

## Live Demo

You can access the live demo of the app [here](http://rparab8.pythonanywhere.com/).

## How to Use

1. Run the Application: Ensure you have the required dependencies installed by running `pip install Flask googletrans==4.0.0 gTTS`. Then, run the Flask application by executing `python app.py`.

2. Access the Web Interface: Open your web browser and navigate to `http://localhost:5000/`.

3. Translate Text:
   - Enter the sentence you want to translate in the "Enter Text" input field.
   - Choose the target language from the dropdown menu labeled "Select Language."
   - Click the "Translate" button to initiate the translation process.

4. Listen to Translation:
   - After translating the text, click the "Play Text" button to hear the translated text as speech.
   - The translated text will be converted to an MP3 audio file and played back through your web browser.

## Technology Stack

- Python
- Flask
- Googletrans
- gTTS (Google Text-to-Speech)

## Installation

To run the application locally, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/text-translator-tts-app.git
   cd text-translator-tts-app
   ```

2. Install the required dependencies:

   ```
   pip install Flask googletrans==4.0.0 gTTS
   ```

3. Run the Flask application:

   ```
   python app.py
   ```

4. Access the web app in your browser at `http://localhost:5000/`.

## Contributing

Contributions to this project are welcome! If you have ideas for improving the app or adding new features, feel free to fork the repository and submit a pull request.

## License

This project is open-source and is licensed under the MIT License. You can find the full license text in the [LICENSE](LICENSE) file.

## Contact

For any questions or inquiries, please contact:

- Name: [Rutik_parab]
- Email: [rutikparab6@gmail.com]

---
