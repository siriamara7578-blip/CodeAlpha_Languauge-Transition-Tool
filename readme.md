# Language Translation Tool

## Project Overview

The Language Translation Tool is a web application that allows users to translate text from one language to another. The application provides an easy-to-use interface where users can enter text, select source and target languages, and get instant translations.

## Features

- Translate text between multiple languages
- User-friendly web interface
- Source language selection
- Target language selection
- Fast and accurate translations
- Built using Python Flask

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Google Translate API (googletrans)

## Project Structure

```
Language_Translation_Tool/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Language_Translation_Tool.git
```

### Step 2: Navigate to Project Directory

```bash
cd Language_Translation_Tool
```

### Step 3: Install Required Packages

```bash
pip install -r requirements.txt
```

## Requirements

Create a file named `requirements.txt` and add:

```text
Flask
googletrans==4.0.0rc1
```

## Running the Application

Start the Flask server:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## How It Works

1. Enter text in the input box.
2. Select the source language.
3. Select the target language.
4. Click the Translate button.
5. The translated text is displayed instantly.

## Example

Input:

```text
Hello, How are you?
```

Source Language:

```text
English
```

Target Language:

```text
Spanish
```

Output:

```text
Hola, ¿Cómo estás?
```

## Future Enhancements

- Voice-to-text translation
- Text-to-speech support
- Translation history
- Dark mode interface
- Support for more languages

## Author

Developed as a mini project using Python Flask and Google Translate API.

