# Resume & Job Description Analyzer

This project analyzes job descriptions and resumes to provide a similarity score and actionable recommendations for improving the alignment between the two. It uses machine learning and natural language processing techniques to compare key phrases, skills, and experience listed in a resume with those required in a job description.

## Table of Contents
1. [Introduction](#introduction)
2. [Usage](#usage)
3. [Features](#features)


## Introduction

This application helps job seekers improve their resumes by comparing them against job descriptions. The tool provides a similarity score and offers recommendations to add or improve specific sections of the resume, such as skills, experience, and qualifications.

## Usage

Once you have the project set up, you can start analyzing resumes and job descriptions.

### Example:
1. Place your resume (`resume.docx`) and job description (`job_description.docx`) in the project folder.
2. Run the script:
    ```bash
    python main.py
    ```

The script will output:
- A similarity score between the resume and job description.
- Actionable recommendations for improving the resume, such as adding specific skills or experience that are missing in the resume compared to the job description.

## Features

- **Text Analysis**: Using Hugging Face transformers, the tool processes the text from resumes and job descriptions to calculate similarities.
- **Actionable Recommendations**: The tool generates recommendations on what to improve in your resume based on the job description.
- **Resume Compatibility**: The tool supports various sectors, including IT, Blockchain, HR, and more.



