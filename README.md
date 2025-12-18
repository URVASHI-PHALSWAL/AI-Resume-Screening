# AI-Resume-Screening
An AI-powered Resume Screening System that ranks and classifies resumes based on a job description using Python, TF-IDF, and Logistic Regression. Perfect for automating candidate shortlisting for data science, AI, and software engineering roles.
# AI-Powered Resume Screening System
# Jupyter Notebook / Python Version

"""
This repository contains an AI-powered Resume Screening System that automatically ranks and classifies resumes based on a job description. 
It uses TF-IDF for feature extraction and Logistic Regression for AI-based suitability prediction. 
This is designed for recruiters, HR teams, and developers to automate candidate shortlisting.
"""

## Features
- Clean and process resumes automatically
- Match resumes to job descriptions
- Rank resumes based on match score
- Predict suitability (Suitable / Not Suitable) using AI
- Easy to use and ATS-friendly

## Technologies Used
- Python 3
- Pandas & Numpy
- Scikit-learn (TF-IDF, Logistic Regression)
- Regex for text cleaning

## Usage
1. Clone or download this repository
2. Open the notebook in Jupyter
3. Add your resumes and job description
4. Run the notebook to get ranked resumes and AI predictions

## Example
```python
sample_resumes = [
    "Data scientist with Python, machine learning, NLP and statistics",
    "Java backend developer with Spring Boot and microservices",
    "AI engineer experienced in deep learning and computer vision"
]

sample_job_description = (
    "Looking for a data scientist with strong Python, machine learning, NLP, and statistical analysis skills"
)

results = screen_resumes(sample_resumes, sample_job_description)
print(results)
```
"""

print(README_md)
