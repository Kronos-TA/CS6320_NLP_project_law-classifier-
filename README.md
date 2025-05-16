#  Legal Document Classifier — NLP Project (CS6320)

This is my final project for the graduate-level Natural Language Processing (NLP) course (CS6320, Spring 2025). The goal is to classify legal documents into their corresponding areas of law, such as Civil, Criminal, Administrative, etc., using machine learning and natural language processing techniques.

---

##  Project Description

Given a set of legal case documents, the goal is to automatically predict the **area of law** each document belongs to. This project includes:
- Preprocessing legal texts (tokenization, lemmatization, stopword removal)
- Feature extraction (TF-IDF, bag-of-words)
- Classification using multiple ML models
- Optional topic modeling using LDA
- Visualization of results and topic distribution

---

##  Project Structure

```
project/
├── data/                  # Legal documents (not included due to size)
├── figure/                # Charts and visualizations
├── Classifier.ipynb       # Main classification notebook
├── topic-modeling.ipynb   # Optional: LDA topic modeling
├── predictions.csv        # Sample output
├── requirements.txt       # Python dependencies
├── README.md              # This file
```

---

##  Models Used

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **XGBoost**
- **Multinomial Naive Bayes**

All models were trained and evaluated on a curated subset of ~100 manually labeled legal documents.

---

##  Lessons Learned

- Legal texts are domain-specific and benefit greatly from domain-specific preprocessing (e.g., removing boilerplate legal terms).
- Logistic Regression with TF-IDF still performs competitively in small datasets.
- Topic modeling requires a larger corpus to generate distinct, coherent topics.

---

##  Improvements & Future Work

- Integrate a Transformer-based model (e.g., BERT or Legal-BERT)
- Expand the dataset to improve generalization
- Explore hierarchical classification if more granular labels are available
- Evaluate cross-lingual models for multilingual legal corpora

---

##  Author

**Ao Tang**  
Graduate Student, CS Department  
University of Texas at Dallas  
Course: CS6320 - Natural Language Processing  
Semester: Spring 2025
