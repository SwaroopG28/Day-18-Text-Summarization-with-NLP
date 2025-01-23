# Text Summarization with NLP

## **Overview**
This project demonstrates a simple **Extractive Text Summarization** technique using **Natural Language Processing (NLP)**. The goal is to condense a given text into a concise summary by identifying and extracting the most important sentences.

---

## **How It Works**
1. **Input Text**:
   - You can provide any text, such as articles, documents, or paragraphs, as input.

2. **Steps Involved**:
   - **Tokenization**:
     - The text is split into sentences and words using **NLTK**.
   - **Stopword Removal**:
     - Common words like "and", "the", etc., are removed to focus on meaningful words.
   - **Word Frequency Calculation**:
     - The frequency of each word is calculated and normalized.
   - **Sentence Scoring**:
     - Sentences are scored based on the sum of frequencies of the words they contain.
   - **Summary Extraction**:
     - The top `n` sentences with the highest scores are selected as the summary.

3. **Output**:
   - The summary is a subset of the most important sentences from the input text.

