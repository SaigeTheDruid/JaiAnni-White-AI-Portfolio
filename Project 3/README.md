# Module 05 – POS Tagging Lab

## Problem Statement

Part-of-speech (POS) tagging assigns grammatical roles—such as noun, verb, adjective—to words in a sentence. It is a foundational NLP task that enables systems to understand text structure, resolve ambiguity (for example, “can” as a verb or noun), and power applications like sentiment analysis, information extraction, and machine translation. This lab examines how POS taggers perform on both clean and real-world text, comparing NLTK and spaCy taggers using different tag sets.

---

## Approach & Methodology

The lab is organized into two parts within a single Jupyter notebook:

### Part 1: In-Class Foundations
- Tagged sample sentences using both **NLTK** and **spaCy**.
- Compared outputs from the **Penn Treebank** and **Universal Dependencies** tag sets.
- Explored ambiguous word usage (e.g. “lead” as noun or verb).
- Benchmarked tagging speed and accuracy between the two libraries.

### Part 2: Homework Application
- Processed messy text samples (e.g. social media posts, transcript snippets).
- Conducted a case study on customer service call transcripts, extracting emotional adjectives, action verbs, and problem-related nouns.
- Built visual summaries of sentiment, urgency indicators, and part-of-speech distributions.
- Performed tagging performance benchmarking across formal, informal, technical, and mixed text types.
- Analyzed challenging edge cases such as garden‑path sentences and domain‑specific jargon.

---

## Results & Evaluation

- **SpaCy** proved faster and more accurate than **NLTK**, particularly on ambiguous or informal text.
- **Universal tag set** offered a clearer, more intuitive tag distribution while **Penn Treebank** provided finer granularity.
- Ambiguous words were correctly disambiguated in context more often with spaCy.
- For customer calls, urgent issues were identified through tags such as modal verbs (“need”, “must”) and negative adjectives.
- Visualizations revealed patterns such as high adjective frequency in complaints and action verbs in requests.
- Performance benchmarks showed spaCy to be significantly faster with fewer unrecognized tokens, even on noisy data.
- Edge case analysis demonstrated failure scenarios in both taggers for sentences with unusual structure or repeated words.

---

## Learning Outcomes

By completing this lab, I gained:

- Practical experience applying POS tagging using **NLTK** and **spaCy**.
- Insight into the strengths and limitations of different tag sets and taggers.
- Skills for handling ambiguous text, slang, and modern formatting in POS pipelines.
- Understanding of how POS tagging can support task-specific analyses such as identifying urgency or sentiment in customer texts.
- Ability to benchmark tools based on execution speed and tagging consistency.
- Proficiency in creating visual summaries (frequency charts, comparison plots) that communicate linguistic insights.
- Awareness of where classical taggers fail (e.g. garden-path sentences, jargon, social media), and how deeper models or domain adaptation could help overcome those issues.

---
