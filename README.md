# Build Project – Data Analysis

## Overview
This notebook walks through a complete data workflow: collecting text, cleaning it, and running some basic sentiment and emotional analysis. The idea was to practice handling messy text data and turn it into something structured and meaningful.

## Contents
- **BuildProject_cleaned_annotated.ipynb** – main notebook with step-by-step code and inline comments  
- **.gitignore** – keeps large/unnecessary files out of the repo  

## Process
1. Pulled in raw text data  
2. Cleaned and normalized it (lowercasing, removing URLs, punctuation, duplicates, lemmatization)  
3. Did some quick exploratory checks (word frequencies, distributions)  
4. Ran sentiment and emotion analysis  
5. Visualized results to see patterns  

## How to Run
Clone the repo and open the notebook:
```bash
git clone git@github.com:purnachandraredddy/Build_Project_Data_Analysis.git
cd Build_Project_Data_Analysis
```

Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn nltk seaborn
```

Then open the notebook in Jupyter or upload it to Colab.

## Notes
- Secrets/tokens have been removed. Use environment variables if needed.  
- This is mainly a practice project, not a polished library.  
