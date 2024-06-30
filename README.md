# 8.-Grammar-and-Spell-Checker-App
# Grammar and Spell Checker App

A simple Python application to check and correct grammar and spelling using the `textblob` and `gingerit` libraries, with a Flask web interface.

## Features

- Checks for grammatical errors in the text.
- Corrects spelling mistakes.
- Simple web-based interface for user input.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/grammar-and-spell-checker-app.git
cd grammar-and-spell-checker-app
python -m venv venv
Activate the virtual environment:
On Windows:
.\venv\Scripts\activate
Install the required dependencies:
pip install -r requirements.txt
Usage
Run the Flask application:
bash

python app.py
Open your web browser and go to http://127.0.0.1:5000/.

Enter the text you want to check and correct in the input form and submit.

The corrected text and grammar mistakes will be displayed on the page.

Example
bash

Enter text to check grammar and spelling: I has a pen. It is bluee.
Corrected Text:  I have a pen. It is blue.
Requirements
Python 3.6+
textblob library
gingerit library
flask library

