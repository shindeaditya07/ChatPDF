# ChatPDF

ChatPDF is a project that allows users to upload PDFs and ask questions based on the content of those PDFs. The application uses the Google Gemini API to process and analyze the PDF content to provide accurate and relevant answers.

## Features

- Upload PDF documents
- Ask questions about the content of uploaded PDFs
- Receive accurate answers based on the content
- Easy-to-use interface

## Getting Started

Follow these instructions to set up and run the project on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.8+
- Pip (Python package manager)
- Google Gemini API key

### Installation

1. Create and activate a virtual environment

    ```sh
    python -m venv venv
    venv\Scripts\activate
    ```

2. Install the required packages

    ```sh
    pip install -r requirements.txt
    ```

3. Set your Google Gemini API key

    Create a `.env` file in the root directory of the project and add your Google Gemini API key:

    ```sh
    GOOGLE_GEMINI_API_KEY=your_api_key_here
    ```

### Usage

1. Run the application

    ```sh
    python app.py
    ```

2. Open your web browser and go to `http://localhost:5000`

3. Upload a PDF document and start asking questions!


## Acknowledgments

- [Google Gemini API](https://developers.google.com/gemini)
- [PyPDF2](https://pypdf2.readthedocs.io/)
