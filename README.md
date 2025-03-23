# **Resume & Job Description Analyzer**

## **Description**  
The **Resume & Job Description Analyzer** is a machine learning-based tool that helps job seekers optimize their resumes by comparing them against job descriptions. It calculates a **similarity score** and provides **actionable recommendations** to improve resume alignment with the job requirements.  

## **Purpose**  
Many job seekers struggle to tailor their resumes for specific job applications. This tool automates the process by identifying **missing skills, experience gaps, and relevant keywords**, ensuring a **better match** between the resume and job description.  

## **Value**  
- **Enhances job application success rates** by optimizing resumes for Applicant Tracking Systems (ATS) and recruiters.  
- **Saves time** by automating resume analysis and comparison.  
- **Provides AI-driven recommendations** tailored to different job industries, including IT, HR, and healthcare.  

## **Technologies Used**  
- **Python** – Core programming language  
- **Natural Language Processing (NLP)** – Text analysis  
- **Sentence Transformers (Hugging Face)** – For semantic similarity comparison  
- **OpenAI GPT-4** – For advanced resume recommendations  
- **Tkinter (GUI Integration)** – For user-friendly interface (future update)  
- **docx (python-docx)** – To process `.docx` resumes and job descriptions  

## **Usage**  
Follow these steps to analyze a resume against a job description:  

1. **Prepare the files**: Place your resume (`resume.docx`) and job description (`job_description.docx`) in the project folder.  
2. **Run the script**:  
   ```bash
   python main.py
   ```  
3. **Output**:  
   - A **similarity score** (how well the resume matches the job description).  
   - **Actionable recommendations** on what to improve in the resume.  

## **Features**  
✔ **Text Analysis** – Uses **machine learning & NLP** to process resume and job description.  
✔ **Similarity Scoring** – Calculates how well a resume matches a job description.  
✔ **AI-Powered Suggestions** – Provides **detailed improvement tips** for resumes.  
✔ **Industry Support** – Works for multiple fields like **IT, HR, healthcare**, etc.  
