# Text Representation Techniques Lab – Module 04

## Problem Statement

Converting raw text into numerical features is a core challenge in NLP. There are various methods—Bag of Words (BOW), TF‑IDF, N‑grams, and embeddings—each with trade‑offs in interpretability, dimensionality, and semantic understanding. This lab guides students through implementing and comparing these techniques to understand their practical strengths and limitations.

---

## Approach & Methodology

1. **Preprocessing**  
   - Used NLTK for tokenization, stop word removal, and stemming.  
   - Prepared both sample data and a subset of movie review texts for real-world context.

2. **Bag of Words & TF‑IDF**  
   - Built BOW and TF‑IDF representations manually and with scikit‑learn.  
   - Applied these to train simple classifiers (Naive Bayes) and analyzed feature importance.

3. **N‑grams Analysis**  
   - Generated unigrams, bigrams, and trigrams to capture short context and negation.  
   - Evaluated how adding n‑grams impacts performance and dimensionality.

4. **Word Embeddings**  
   - Loaded pretrained GloVe or Word2Vec vectors.  
   - Explored word similarities and analogies.  
   - Compared embedding-based representations with sparse methods.

5. **Comparison & Applications**  
   - Trained classification models using each representation method and compared accuracy.  
   - Performed a mini search engine demo using TF‑IDF similarity.  
   - Compiled a table of real‑world NLP applications and mapped typical representation choices.

6. **Ethical Considerations**  
   - Reflected on bias in word embeddings, privacy concerns, fairness, and interpretability.  
   - Listed best practices to mitigate these risks.

---

## Results & Evaluation

- **Classification**  
  - BOW and TF‑IDF models achieved reasonable accuracy on sentiment classification of movie reviews.  
  - Addition of bigrams improved capture of context like “not good” but increased feature count.  
  - Word embeddings provided dense, semantically rich features and often matched or exceeded sparse representations in performance.

- **Feature Analysis**  
  - Top predictive features for positive and negative sentiment were extracted from model coefficients.  
  - Example: words like `excellent`, `great`, `boring`, `terrible`.

- **Similarity and Search**  
  - TF‑IDF similarity enabled a simple but effective search demo for ranking relevant documents.  
  - Embeddings allowed semantic relationships like “movie ↔ film” or analogies like “king – man + woman ≈ queen”.

- **Application Table**  
  - Mapped representation methods to 10 common NLP use cases (e.g. search engines, recommendation systems, sentiment analysis, chatbots, spam detection), describing the key challenges each method addresses.

- **Ethics**  
  - Highlighted examples of bias in pretrained embeddings (e.g. gender stereotypes, cultural underrepresentation).  
  - Emphasized strategies like bias testing, inclusive datasets, transparency, and ongoing monitoring.

---

## Learning Outcomes

Working on this lab, I gained the following insights:

- **Technical proficiency** with text transformation methods and understanding when to use each one.  
- **Appreciation of trade‑offs** between sparse vs dense features, interpretability, memory usage, and semantic understanding.  
- **Practical experience** building end‑to‑end pipelines for text classification and document retrieval.  
- **Awareness of ethical considerations**, including bias, fairness, and privacy in representation methods.  
- **Critical thinking** about how representation choices affect downstream application quality in real-world settings.

---

