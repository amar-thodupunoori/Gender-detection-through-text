**README**

This repository contains code and data for a Natural Language Processing (NLP) project analyzing gender classification based on Twitter text data. The project includes data preprocessing, exploratory data analysis, and building machine learning models for gender classification.

**Project Overview:**
The project aims to predict the gender of Twitter users based on their tweets. It involves the following steps:

1. **Data Collection:** The dataset used in this project is stored in the file "Information.csv".

2. **Data Preprocessing:** The data is cleaned and preprocessed to remove noise and irrelevant information. Text data is processed to remove stopwords, punctuation, and perform stemming.

3. **Exploratory Data Analysis (EDA):** Basic statistical analysis and visualizations are performed to gain insights into the data distribution and characteristics.

4. **Model Building:** Three classification models are implemented for gender classification:
   - Naive Bayes
   - Random Forest
   - Decision Tree

5. **Model Evaluation:** The models are evaluated using accuracy score to measure their performance.

**Files:**
- **Project.ipynb:** Jupyter notebook containing the Python code for the project.
- **Information.csv:** Dataset containing Twitter user information.

**Libraries Used:**
- numpy
- matplotlib
- pandas
- seaborn
- re
- nltk
- spellchecker
- sklearn
