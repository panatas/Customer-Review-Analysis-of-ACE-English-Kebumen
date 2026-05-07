# Customer-Review-Analysis-of-ACE-English-Kebumen

## Overview
This project analyzes customer reviews from Google Maps to understand how students perceive ACE English Kebumen. The objective is to extract meaningful insights from unstructured text data using basic Natural Language Processing (NLP) techniques.

## Tools
- Phyton
- Pandas
- Regular Expression
- Counter
- Matplotlib

## Dataset
- Source    : Google Maps reviews (manually collected)
- Language  : Indonesian & English (mixed)
- Format    : CSV File

## Methodology
### 1. Data Collection
Reviews were manually compiled and stored in a structured dataset.
### 2. Text Preprocessing
The following steps were applied:
- lowercase information
- removal of punctuation, numbers, and special characters
- normalization of repeated characters (example : "sangatttt" -> "sangat")
- normalization of repeated words (example : "baik baik" -> "baik-baik")
- Indonesian suffix normalization (example : "tutornya" -> "tutor")
### 3. Tokenization
Reviews were split into individual words for analysis.
### 4. Stopword Removal
A combination approach was used:
- English stopwords
- Indonesian stopwords
- dataset specific stopwords identified through exploratory analysis
### 5. Word Frequency Analysis
There are two metrics were used:
- Word Percetage (%)
  measure how important a word is in the overall dataset
- Review Density (%)
  measure how frequently a word appears across reviews
### 6. Visualization
Most used word were visualized using horizontal bar charts.

## Key Insights
- Student associate the course with *"English learning"*, as shown by frequent mentions of "english", "inggris", "bahasa".
- The learning experiences is perceived as *"fun and good"*, with words like "good", "seru", "fun", and "bagus".
- *Tutor quality is a key factor*, with consistent mentions of "tutor", "ramah" and "baik". It's highlighting the importance of teaching style and friendliness.
- The reviews reflect a *bilingual learning environment*, combining Indonesian and English which is supports accesbility for learners.

## Conclusion
The analysis shows that ACE English Kebumen is perceived as:
- an enganging learning environment
- supported by friendly and effective tutors
- focused on interactive and enjoyable learning
