# Resume Screening Project

## Overview

This project focuses on automating the resume screening process using Natural Language Processing (NLP) techniques. The aim is to help recruiters quickly identify suitable candidates by analyzing and classifying resumes based on predefined criteria. The project includes a web application, "Resume Screening App," built using Streamlit for an interactive and user-friendly interface.


## Features


Text Preprocessing: 

Clean and preprocess resume text using regular expressions (regex).



Stopwords Removal: 

Remove common stopwords using the NLTK library to enhance text analysis.



Text Vectorization: 

Convert textual data to numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) technique.



Model Training: 

Train a multi-label classification model from scratch using OneVsRestClassifier.



Interactive Dashboard: 

Built with Streamlit, allowing users to upload resumes and view screening results.



# Project Structure

resume-screening-project/
│
├── data/
│   ├── raw_resumes/                                       # Raw resume files
│
├── models/
│   └── tfidf.pkl                                           # Text to vector convertor
│   └── trained_model.pkl                                   # Trained classification model
│
├── notebooks/
│   └── data_preprocessing_and_model_training.ipynb         # Jupyter notebook for preprocessing
│
├── src/
│   └── resume_screening_app.py     # Streamlit app script
│
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies




# Running the Streamlit App

Launch the interactive resume screening app:

streamlit run src/resume_screening_app.py

![Screenshot 2024-06-12 222502](https://github.com/VarshaYK/NLP-Resume-screening-App/assets/31321685/285eb8f9-1a24-4cde-ad3b-833aa349b424)

