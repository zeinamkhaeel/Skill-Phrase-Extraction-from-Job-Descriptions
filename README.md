# 🧠 Job Market NLP: Skill & Phrase Extraction from Job Descriptions

This project extracts structured skills and phrases from messy, unstructured job descriptions using NLP techniques like:
- Noun chunking (`spaCy`)
- Fuzzy keyword matching
- Text cleaning and filtering

## 🔍 Example Output
Job Title: **Medical Laboratory Assistant**  
Extracted Phrases:
- `lab-specific experience`
- `body fluids`
- `laboratory system`

## 🛠️ Tools Used
- Python, pandas, spaCy, fuzzy matching
- Dataset: 2,000 job postings (subset of larger scraped dataset)


## 📁 Files
- `postings.csv` — raw input dataset you can downloaded from Kaggle https://www.kaggle.com/datasets/arshkon/linkedin-job-postings
- `job_skill_extraction.ipynb` — full preprocessing and NLP pipeline

