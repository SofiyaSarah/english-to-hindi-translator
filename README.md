
# English to Hindi Translation Model

## Overview
This project is a simple **English-to-Hindi translation tool** built using the `Helsinki-NLP/opus-mt-en-hi` model from Hugging Face. It allows users to input English text and get its Hindi translation. The project is designed to run in **Google Colab**, making it accessible for beginners without needing local hardware setup.

## Features
- Translates English text to Hindi using a pretrained MarianMT model.
- Runs on Google Colab with free GPU support for faster processing.
- Easy-to-use code with a single input cell for translations.
- Option to save the model to Google Drive for reuse.

## Prerequisites
- A **Google Colab** account (free tier works).
- Internet connection (for downloading the model initially).
- Optional: Google Drive to save the model for persistent use.

## Installation
1. Open the project in Google Colab:
   - [Link to Colab Notebook]([https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK](https://colab.research.google.com/drive/1VXx-57TwdcohzlmzTLLEd1HpFZGn6Sxc?usp=sharing))
2. Ensure Colab runtime is set to GPU (optional for faster processing):
   - Go to `Runtime > Change runtime type > Select GPU`.
3. Run the cells in order as described below.

## Usage
1. **Install Libraries**: Run the first cell to install `transformers` and `sentencepiece`.
2. **Load Model**: Run the second cell to load the pretrained `Helsinki-NLP/opus-mt-en-hi` model.
3. **Translate**: Modify the `english_text` variable in the fourth cell with your English text, then run to see the Hindi translation.
4. **Example**:
   ```python
   english_text = "Hello, how are you?"
   # Output: नमस्ते, आप कैसे हैं?
