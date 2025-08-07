# NewsBot Intelligence System — Midterm Project

## Problem Statement
Digital news platforms generate volumes of textual content across diverse categories like business, sports, and politics. Manually processing and analyzing this content for classification, sentiment, and insight extraction is time-consuming and labor-intensive. The challenge is to build an efficient NLP pipeline that automates news categorization and delivers meaningful linguistic insights.

---

## Approach and Methodology
We implemented a modular NLP pipeline on the BBC News dataset covering five categories:

1. **Text Preprocessing**
   - Lowercasing, punctuation/digit removal, tokenization, stopword removal, and lemmatization via spaCy.

2. **Feature Extraction**
   - TF‑IDF vectorization (uni‑ and bigrams, limited vocabulary for efficiency).

3. **Text Classification**
   - Trained Multinomial Naive Bayes and Linear SVM classifiers.
   - Evaluated using classification reports and confusion matrices.

4. **Linguistic Analysis**
   - Named Entity Recognition (NER) for identifying persons, organizations, and locations.
   - Sentiment analysis using VADER to label sentiment as positive, neutral, or negative.
   - Syntactic parsing with spaCy to extract part-of-speech tags and dependency relations.

---

## Results and Evaluation
- **Classification Accuracy**: SVM performed significantly better than Naive Bayes with a narrower error margin in confusion analysis.
- **NER Output**: Successfully captured key entities, such as major organizations and public figures, enhancing interpretability.
- **Sentiment Trends**: Sports articles skewed positive, while politics and business articles frequently exhibited neutral or negative sentiment.
- **Structural Insights**: POS tagging and dependency parsing revealed consistent sentence structures, aiding downstream processing.

---

## Learning Outcomes
- Gained proficiency in building an end-to-end NLP workflow—from data cleaning to model evaluation.
- Explored text classification techniques using TF‑IDF, Naive Bayes, and SVM.
- Applied advanced NLP tools like spaCy, VADER, and scikit-learn for practical insight extraction.
- Developed skills in analyzing NLP outputs and visualizing linguistic patterns for interpretability.

