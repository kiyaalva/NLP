📘 NLP Basics: A Quick Reference

🎯 Objective
This project is a concise documentation and hands-on guide to understanding the fundamentals of Natural Language Processing (NLP). It focuses on the preprocessing phase — the cornerstone of any NLP pipeline.

🧹 Core Concepts Covered
•	Text Cleaning

•	Removing punctuation and special characters

•	Lowercasing text

•	Tokenization

•	Splitting sentences into words (tokens)

•	Stopword Removal

•	Removing common English words that add little value (e.g., the, and, is)

•	Lemmatization

•	Converting words to their base/root form (e.g., running → run)

•	Corpus Building

•	Creating cleaned, structured data ready for modeling

⚠️ Common Hurdles in NLP
•	Encoding issues with non-ASCII characters

•	Over-removal of useful words during stopword filtering

•	Lemmatization inconsistencies (e.g., lack of context for POS tagging)

•	Memory errors for large text corpora

•	Library-related typos (e.g., stopwords.word() vs stopwords.words())

🛠 Tools & Libraries
•	nltk – Natural Language Toolkit for stopwords, lemmatization

•	re – Regular expressions for text cleaning

•	pandas – Handling text in tabular format (DataFrame)

•	sklearn (optional) – For feature extraction like TF-IDF
