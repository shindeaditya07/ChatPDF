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

1. Clone the repository

    ```sh
    git clone https://github.com/yourusername/chatpdf.git
    cd chatpdf
    ```

2. Create and activate a virtual environment

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages

    ```sh
    pip install -r requirements.txt
    ```

4. Set your Google Gemini API key

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

## Project Structure

- `app.py` - The main application file
- `requirements.txt` - List of required Python packages
- `templates/` - Directory for HTML templates
- `static/` - Directory for static files (CSS, JS, images)
- `utils/` - Utility functions for processing PDFs and interacting with the Google Gemini API

## Contributing

We welcome contributions to the project! Here are some ways you can help:

- Report bugs
- Suggest features
- Submit pull requests

### How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a pull request

## Acknowledgments

- [Google Gemini API](https://developers.google.com/gemini)
- [PyPDF2](https://pypdf2.readthedocs.io/)
