
# 📘 Lecture Notes Expander (Gemini)

Convert your class or lecture notes into fully explained AI-generated notes.

## Features

* Extracts text from PDFs (with OCR fallback for scanned pages)
* Expands notes into textbook-style explanations
* Adds examples, analogies, and step-by-step derivations
* Outputs to Word (`.docx`)

## Usage

1. Clone the repo:

```bash
git clone <repo-url>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Paste your Google Gemini API key in `api_keys.py`:

```python
def get_google_gemini():
    return "YOUR_GOOGLE_GEMINI_API_KEY_HERE"
```

4. Run the app:

```bash
python app.py
```

5. Open the Gradio interface and upload your PDF to generate notes.

## Requirements

* Python 3.10+
* Dependencies listed in `requirements.txt`


Do you want me to also **create the minimal `requirements.txt`** for this README?
