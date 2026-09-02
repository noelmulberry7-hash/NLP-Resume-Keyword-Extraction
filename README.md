# NLP-Based Resume Keyword Extraction and Job Description Matching Using TF-IDF

## Problem

The project aims to extract important keywords and skills from resumes and compare them with the requirements of a job description.

## Objectives

* To preprocess resume text using NLP techniques.
* To extract important keywords from resumes.
* To use TF-IDF for text representation.
* To match resumes with a job description using Cosine Similarity.
* To rank resumes based on their matching scores.

## Dataset

The project uses the **AI Resume Analyzer – Job Role Prediction Dataset** containing 10,000 resume records with information such as resume text, education, experience, skills, job role, and category.

## Methodology

1. Data loading and exploration
2. Text preprocessing
3. TF-IDF feature extraction
4. Resume keyword extraction
5. Job description matching
6. Cosine Similarity calculation
7. Evaluation and ranking

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Regular Expressions

## Results

The highest resume matching score obtained was **57.12%** for Resume ID **R007150**, with the job role **Data Scientist**.

## Conclusion

The project demonstrates how NLP techniques can be used to extract keywords from resumes and identify resumes that are more relevant to a given job description.
