# Resume_Classification_System

An intelligent machine learning-powered web application that automatically classifies resumes into specific job categories using NLP and TF-IDF vectorization.
🎯 Overview
This project uses machine learning to analyze and categorize resumes into four distinct job categories:

React Developer
Workday Specialist
SQL Developer
PeopleSoft Specialist

The system extracts skills from resumes, processes the text, and provides accurate classification with confidence scores.
✨ Features

Multi-Format Support: Upload resumes in PDF, DOCX, or DOC formats
Skill Extraction: Automatically identifies relevant technical skills
Real-time Classification: Instant categorization with confidence metrics
Interactive UI: Built with Streamlit for a clean, user-friendly experience
Confidence Visualization: Bar charts and progress indicators for all category probabilities
Text Input Option: Classify resumes by pasting text directly

🛠️ Technologies Used

Python 3.x
Streamlit: Web application framework
scikit-learn: Machine learning model and TF-IDF vectorization
PyPDF2: PDF text extraction
python-docx: DOCX file processing
docx2txt: DOC file processing
Pandas: Data manipulation and visualization
Model Performance

Accuracy: 100% (on training dataset)
Vectorization: TF-IDF with skill-based feature engineering
Classifier: Machine Learning model (trained on labeled resume data)

🔍 How It Works

Text Extraction: Reads resume from uploaded file
Text Cleaning: Removes URLs, special characters, and normalizes text
Skill Detection: Identifies domain-specific keywords
Feature Engineering: Combines cleaned text with extracted skills
Vectorization: Transforms text using TF-IDF
Classification: Predicts category with probability scores
