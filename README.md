# Machine Learning Task 03 – Resume / Candidate Screening System

## Project Overview
This project focuses on building a Machine Learning–based Resume Screening System using Natural Language Processing (NLP).

In real-world hiring processes, recruiters receive hundreds of resumes for a single job role. Manually reviewing each resume is time-consuming, inconsistent, and prone to human bias. 

This system automates resume screening by extracting skills, comparing resumes with job descriptions, and ranking candidates based on suitability.

---

## Objective

The main objectives of this project are:

- Read and process resume text data (PDF/Text format)
- Extract relevant skills and keywords
- Compare resumes with a given job description
- Calculate similarity scores
- Rank candidates based on role suitability
- Highlight missing or required skills

---

## Technologies Used

### Programming & Development
- Python
- Jupyter Notebook
- VS Code
- GitHub

### Libraries & Tools
- Pandas
- NumPy
- NLTK (text preprocessing & tokenization)
- spaCy (skill extraction & NLP pipeline)
- Scikit-learn (vectorization & similarity calculation)

---

## Methodology

1. Data Collection  
   Resume text data and a job description were used as input.

2. Text Preprocessing  
   - Lowercasing  
   - Removing stopwords  
   - Tokenization  
   - Cleaning special characters  

3. Skill Extraction  
   - Identifying relevant technical skills and keywords  
   - Matching them with job description requirements  

4. Feature Extraction  
   - Converting text into numerical format using TF-IDF  

5. Similarity Calculation  
   - Calculating cosine similarity between resume and job description  

6. Candidate Ranking  
   - Ranking candidates based on similarity scores  

---

## Output

- Extracted skills from resumes  
- Resume-to-job similarity scores  
- Ranked list of candidates  
- Identification of missing or required skills  

---

## Business Impact

This system helps organizations:

- Shortlist candidates faster  
- Reduce manual screening workload  
- Improve hiring efficiency  
- Ensure more consistent and data-driven decisions  

---

## Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to automate resume screening and candidate ranking.

By building a decision-support system instead of just a prediction model, this project reflects real-world HR-tech applications and improves the overall recruitment process.
