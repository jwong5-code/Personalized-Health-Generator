# Medical Report Generation

This repository contains a Python script for generating a personalized medical report in PDF format. The script collects patient information, generates a detailed medical description using OpenAI's GPT-3.5, and compiles the data into a well-structured PDF report.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)
- [Additional Notes](#additional-notes)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- Collects patient information interactively
- Generates detailed medical descriptions using OpenAI's GPT-3.5
- Creates a PDF report with patient information, medical history, lifestyle data, current symptoms, and recommendations
- Ensures data integrity and user-friendly input

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/medical-report-generation.git
   cd medical-report-generation
2. **Create a virtual environment and activate it:**
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. **Install the required packages:**
   pip install -r requirements.txt

## Usage

Set your OpenAI API key:
Ensure you have your OpenAI API key stored in an environment variable named `OPENAI_API_KEY`.

### Run the script:

bash
python generate_report.py

## Usage Instructions

### Follow the prompts to enter patient information:
The script will interactively ask for the patient's name, age, gender, medical history, lifestyle details, current symptoms, and any additional information.

### Check the generated PDF:
The PDF report will be saved to the specified path (e.g., `C:/Users/joshu/Documents/Desktop/health_report1.pdf`). Ensure the directory exists or the script will create it.

## Configuration

### Environment Variables:
- `OPENAI_API_KEY`: Your OpenAI API key for generating medical descriptions.

### File Paths:
- Adjust the file paths in the script to match your preferred directory structure.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Additional Notes
- Ensure you have an active internet connection when running the script, as it requires access to the OpenAI API.
- Customize the PDF layout and content as needed by modifying the `create_pdf` function in the script.

