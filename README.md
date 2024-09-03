
# Data Summarization Project

## Overview

This project provides a simple web interface for summarizing large pieces of text. The application utilizes a pre-trained model from Hugging Face's `distilbart-cnn-12-6` to perform text summarization. Users can input text data into the form, specify the desired summary length, and receive a summarized version of the text. The application is built using Flask for the backend and Tailwind CSS for the frontend styling.

## Features

- User-friendly interface to input large text data.
- Option to specify the desired summary length.
- Real-time processing using a pre-trained model for summarization.
- Output display for the summarized text.
- Copy functionality to easily copy the summarized text.
- Responsive design with a clean, modern UI.

## Technologies Used

- **Frontend**: HTML, CSS (Tailwind CSS), JavaScript
- **Backend**: Flask (Python)
- **API**: Hugging Face API for text summarization
- **Deployment**: Can be deployed on platforms like Heroku, AWS, etc.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.12.4
- Pip (Python package installer)

 
 ## Installation

1. **Create and activate a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows use `venv\Scripts\activate`
    ```

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```
