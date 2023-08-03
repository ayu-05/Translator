# Instant-Translator
# Instant Translator

This is a simple Python program that uses the tkinter library to create a graphical user interface (GUI) for translating English text to any language using the TextBlob language translation API. The program allows you to enter English text, select a target language, and instantly obtain the translation.

## Dependencies
- Python 3.x
- tkinter library (built-in)
- textblob library (`pip install textblob`)

## Usage

1. Clone or download the source code from the repository.
2. Install the `textblob` library if you haven't already (`pip install textblob`).
3. Run the Python script `translator.py` using a Python IDE or by running the command `python translator.py` in your terminal.
4. The GUI window will appear, providing the translation interface.

## Interface

The GUI window contains the following components:

- **Label**: Displays the heading "Translate from English to any language".
- **Label**: Indicates the input text box with the text "Type Anything".
- **Input Text Box**: A scrollable text box where you can enter the English text that you want to translate.
- **Label**: Indicates the translation target with the text "Translate to:".
- **Translate Button**: Click this button to translate the input text to the selected language (by default, it's set to translate to Hindi).
- **Output Text Box**: A scrollable text box where the translated text will be displayed.
- **Label**: Displays the credit label "© Prakhar Doneria" at the bottom of the window.

To translate the English text to another language:
1. Enter the English text in the input text box.
2. Click the "TRANSLATE TO HINDI" button to translate the text to Hindi. You can modify the `toLang` function parameter in the code to translate to a different language if desired.
3. The translated text will be displayed in the output text box.

Please note that the accuracy and quality of the translations depend on the underlying TextBlob language translation API.
