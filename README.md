# Image Text Extractor

A Streamlit application that uses Google's Gemini AI to extract text from images and create editable Word documents.

## Features

- **Image Upload**: Support for multiple image formats (PNG, JPG, JPEG, GIF, BMP, WebP)
- **AI-Powered Text Extraction**: Uses Google Gemini Vision API for accurate text recognition
- **Multiple Extraction Modes**: 
  - Comprehensive: Extracts all text with structure preservation
  - OCR Only: Simple text extraction
  - Structured: Organized output with headings
- **Editable Output**: Edit extracted text before downloading
- **Multiple Export Formats**: Download as Word document (.docx) or plain text (.txt)
- **User-Friendly Interface**: Clean Streamlit interface with real-time preview

## Setup

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Get Gemini API Key**:
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Sign in and create an API key
   - Keep it secure for use in the application

3. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Configure API**: Enter your Gemini API key in the sidebar
2. **Upload Image**: Choose an image file containing text
3. **Select Mode**: Pick your preferred extraction method
4. **Extract Text**: Click the extract button to process the image
5. **Edit & Download**: Review, edit, and download as Word or text file

## Requirements

- Python 3.8+
- Google Gemini API key
- Internet connection for API calls

## File Structure

```
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## API Usage Notes

- The Gemini API has usage limits and may require billing setup
- Images are processed securely through Google's API
- No images or text are stored locally by this application