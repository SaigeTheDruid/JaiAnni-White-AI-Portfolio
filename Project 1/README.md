# Lab 02 – Basic NLP Preprocessing Techniques

**Course:** ITAI‑2373 – Natural Language Processing  
**Name**: Jai'Anni White 

---

## Problem Statement

Working with raw text is inherently messy—full of punctuation, casing inconsistencies, stop words, and irregular forms. Most machine learning models can’t interpret linguistic nuance directly. My task was to explore how preprocessing transforms raw text into structured, meaningful input that algorithms can use effectively.

---

## Approach and Methodology

I worked through a fully-coded Jupyter notebook (provided as part of the lab) using two industry-standard libraries: **NLTK** and **spaCy**. I executed each code cell, paid close attention to the output, and answered all reflection questions embedded in the notebook.

My methodology included:

- Tokenizing text into words and sentences  
- Removing stop words and normalizing casing  
- Applying stemming and lemmatization to reduce word forms  
- Cleaning text (removing punctuation and non‑alphabetic characters)  
- Comparing results side-by-side between NLTK and spaCy  
- Building full, reusable preprocessing pipelines to apply to sample data

---

## Results and Evaluation

By executing and analyzing both pipelines, I observed:

- **spaCy** generally produced more accurate lemmatization and robust token boundaries  
- **NLTK stemming** sometimes led to non‑words or over‑generalization (e.g. “running” → “run”)  
- The choice of lowercasing, stop‑word removal, and normalization made a notable difference in token distribution  
- Reflection questions highlighted how different preprocessing steps can affect word counts, vocabulary size, and downstream token features

Overall, spaCy was more polished for real-world use, while NLTK provided deeper visibility into individual transformations, making it more educational for learning pruning and reduction techniques.

---

## Learning Outcomes

This lab helped me understand the essential role of preprocessing in NLP:

- I now appreciate why each preprocessing step—tokenization, stop‑word removal, stemming vs lemmatization—is vital for clean, interpretable text input.
- I learned to evaluate trade‑offs between algorithmic speed, accuracy, and readability when selecting preprocessing tools.
- I saw how small differences in cleaning decisions (e.g., including punctuation or not) can drastically alter token distributions.
- I recognized how preprocessing choice is foundational—upstream decisions influence everything from vocabulary size to model performance.
- I developed the ability to build modular, reproducible pipelines that can be adapted to different NLP tasks or datasets.


