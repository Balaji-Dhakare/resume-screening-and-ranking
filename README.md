# AI-Powered Resume Screening & Candidate Ranking System

## Overview
This project is an AI-powered system designed to automate the process of resume screening and candidate ranking. It compares resumes against a provided job description using natural language processing (NLP) techniques. The system helps recruiters save time, improve efficiency, and minimize biases in the hiring process.

---

## Features
- **Automated Resume Ranking:** Upload resumes in PDF format and rank them based on their relevance to the job description.
- **Interactive Interface:** User-friendly interface built using Streamlit.
- **Text Processing:** Utilizes TF-IDF and Cosine Similarity for textual analysis and ranking.
- **Output Visualization:** Displays ranked results in a table format.
- **Sample Data:** Includes sample resumes and job descriptions for testing.

---

## How It Works
1. Users input a job description into the text field.
2. Users upload multiple resumes in PDF format.
3. The system:
   - Extracts text from the resumes.
   - Preprocesses the text (e.g., removing stop words, special characters).
   - Converts the text into numerical vectors using TF-IDF.
   - Calculates the similarity of each resume to the job description using Cosine Similarity.
4. Resumes are ranked based on similarity scores.
5. Results are displayed in a table.

---

## Installation

### Requirements
- Python 3.8+
- Required libraries:
  - `streamlit`
  - `pandas`
  - `sklearn`
  - `PyPDF2`

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/resume-screening.git
   cd resume-screening
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

---

## Usage
1. Open the Streamlit app in your browser.
2. Enter the job description in the designated text box.
3. Upload one or more resumes in PDF format.
4. View the ranked results displayed in a table format.

---

## Example Output

 screenshot of the output is given in repo :


In this example, resumes were uploaded, and the system ranked them based on their relevance to the provided job description.

---

## Sample Data
The project includes sample resumes and a job description to test the functionality. You can find them in the repo

---

## Future Enhancements
- Integrate advanced NLP models like BERT or GPT for improved accuracy.
- Add support for parsing other file formats like DOCX.
- Include visualization of similarity scores using graphs.
- Incorporate feedback mechanisms to refine ranking results.

---
