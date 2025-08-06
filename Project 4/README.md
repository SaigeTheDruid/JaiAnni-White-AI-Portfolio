# Module 07: Sentiment & Emotion Analysis Lab

This lab challenges you to build systems that detect sentiment and emotion in both text and speech. You will explore rule-based tools, machine learning classifiers, speech feature extraction, and multimodal fusion.

---

## Problem Statement

Understanding emotions and opinions in user-generated content is essential for applications like customer service, mental health tools, and content moderation. This lab focuses on identifying emotional tone in text and speech, diagnosing challenges in sarcasm, cultural context, noisy inputs, and multimodal signals.

---

## Approach & Methodology

The notebook guides you through six stages:

1. **Setup & Installation**  
   Installation of required NLP and audio libraries and reminder activities from Labs 1–6.

2. **Rule-Based Text Sentiment**  
   Use VADER and TextBlob to score a variety of textual inputs, comparing their strengths and weaknesses.

3. **Text-Based Machine Learning**  
   Build classifiers using TF‑IDF, logistic regression, and ensemble methods, then evaluate their emotion prediction accuracy.

4. **Speech Emotion Detection**  
   Extract audio features using `librosa`, then train and evaluate a classifier to detect emotional tone in voice samples.

5. **Multimodal Fusion**  
   Combine textual and audio representations into a single feature vector, then train a classifier to capture emotion cues across modalities.

6. **Bias, Fairness & Real-World Applications**  
   Analyze emotion misclassification across demographics and cultural contexts, and reflect on ethical concerns in deployment.

---

## Results & Evaluation

- **VADER vs TextBlob**:  
  - VADER handled social and slang text better; TextBlob offered cleaner polarity scores in formal review text.  
  - Each struggled with irony, cultural expressions, and neutral sentiment.

- **ML Classifiers (Text)**:  
  - Logistic regression and random forest classifiers achieved around 80% accuracy on sentiment classes.  
  - Most informative features aligned with intensifiers, negation terms, and emotional adjectives.

- **Speech Emotion Classifier**:  
  - Yielded reasonable accuracy, particularly for expressive emotion like “angry” and “happy”; neutral and subtle emotions were more difficult to classify.

- **Multimodal Fusion**:  
  - Combining modalities often improved classification accuracy by 3–5%, reducing errors from ambiguous textual or audio-only inputs.

- **Ethical Insights**:  
  - Rule-based systems tended to misinterpret dialects or sarcastic phrasing.  
  - Cultural idioms and tone often led to false positives or negatives.  
  - Reflection emphasized the importance of bias testing, inclusive data, and transparency.

---

## Learning Outcomes

By completing this lab, I achieved the following:

- Ability to implement sentiment analysis using both rule-based tools and machine learning.
- Experience extracting emotional features from speech and combining them with text data.
- Understanding the benefits and limitations of each approach in various real-world settings.
- Insight into multimodal fusion as a method for more robust emotion detection.
- Awareness of bias, fairness, and cultural impact in emotionally sensitive AI systems.
- Skills in visualizing and interpreting emotion detection outputs for actionable insights.

---
