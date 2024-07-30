# Application Tracking System

This is an **Application Tracking System (ATS)** designed to evaluate resumes against job descriptions in tech fields like software engineering, data science, data analysis, and big data engineering. The ATS uses Google Gemini Pro's Generative AI model to analyze the resume and provide actionable feedback, including a job description match percentage, missing keywords, and a profile summary.

## Features

- **Upload Resume:** Upload resumes in PDF format for analysis.
- **Job Description Matching:** Compare resumes against a provided job description.
- **Missing Keywords:** Identify keywords missing from the resume.
- **Profile Summary:** Generate a profile summary and suggestions for improvement.

## Installation

To get started, clone this repository and set up your environment.

```

Create a virtual environment:


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
```
Install dependencies:


pip install -r requirements.txt
```
#Set up API Key:

Create a .env file in the root directory of the project and add your Google API key:

```
GOOGLE_API_KEY=your_google_api_key_here
Usage
Run the Streamlit application:


streamlit run app.py
```

#Upload Resume:

Go to http://localhost:8501 in your web browser.
Paste the job description into the designated text area.
Upload a PDF file of the resume.
Click "Submit" to get the evaluation results.

#File Structure
main(2).py: Main application code using Streamlit for the front-end interface.
requirements.txt: Python dependencies for the project.

#Dependencies
Streamlit: For creating the interactive web application.
PyPDF2: For extracting text from PDF files.
python-dotenv: For loading environment variables.
google-generativeai: For accessing Google's Gemini Pro model.

#Contributing
Contributions are welcome! Please open an issue or submit a pull request if you'd like to contribute to the project.
