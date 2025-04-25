# **CVlyzer** - Resume & Job Description Analyzer

## **Description**  
**CVlyzer** is a Python-based tool designed to analyze and compare your resume with a job description. By leveraging AI and natural language processing (NLP) techniques, **CVlyzer** provides a **similarity score** and **actionable recommendations** to improve your resume’s alignment with job requirements.

## **Purpose**  
Many job seekers struggle to tailor their resumes to specific job descriptions. **CVlyzer** automates this process by:
- Identifying missing skills, experience gaps, and relevant keywords.
- Providing **AI-driven recommendations** for resume improvements.
- Enhancing job application success rates.

## **Value**  
- **Improves your resume**: Enhances the likelihood of passing through Applicant Tracking Systems (ATS) and impressing recruiters.
- **Saves time**: Automates the resume optimization process, making job applications more efficient.
- **Custom recommendations**: Tailored suggestions for improvement based on the job description and resume comparison.

---

## **Technologies Used**  
- **Python** – Core programming language.
- **Natural Language Processing (NLP)** – For text analysis and comparison.
- **ttkbootstrap** – For GUI styling.
- **PyPDF2** – For handling and extracting text from PDF resumes.
- **python-docx** – For handling DOCX resumes.
- **requests** – For making HTTP requests to interact with the AI model.
- **Ollama** – For providing AI-powered resume analysis.

---

## **Setup Instructions**  

### 1. Clone the Repository
Clone **CVlyzer** to your local machine using Git:
```bash
git clone https://github.com/deadpool-kha/CVlyzer.git
cd CVlyzer

 ``` 

### 2.Install Python
Ensure you have Python 3.x installed. If you don't have Python installed, download and install it from the official Python website.

Check your Python version:
```bash
python --version

```
3. **Install Required Libraries**  
   Install the necessary dependencies using the following command:
   
   ```bash
   pip install -r requirements.txt
    
   ```
   This will install:
    ttkbootstrap
    requests
    python-docx
    PyPDF2
    jupyter

## 4. Install and Start Ollama

Ollama is required to process AI-driven analysis. You can download Ollama from the [Ollama website](https://ollama.com).

Once Ollama is installed, start the service with the following command:

```bash
ollama serve

```
##5. Launch Jupyter Notebook
   Run Jupyter Notebook to launch the CVlyzer application:
   ```bash
jupyter notebook

```
    
# How to Use the App

## 1. Upload Your Files
- Upload your resume (in .docx or .pdf format).
- Upload the job description (also in .docx or .pdf format).

## 2. Start Analysis
- Click the "Run" button in the notebook to start the analysis.
- The app will process your resume and job description, and return:
  - A similarity score (how well your resume matches the job description).
  - Actionable recommendations on how to improve your resume.

        


