# NLP Text Summarization Tool

## Project Overview
A web-based Natural Language Processing application designed to automatically summarize long articles and documents into concise, meaningful summaries. The tool utilizes **Extractive Summarization** techniques to identify and retain the most significant sentences from the source text, helping users save reading time.

*(Note: This project was developed as part of my academic coursework. The source code is currently archived, and this repository serves as a portfolio showcase of the system design, functionality, and UI).*

## Key Features
- **Smart Summarization:** Uses statistical NLP algorithms to rank and extract key sentences.
- **Real-time Processing:** Instantly processes large blocks of text.
- **PDF Export:** Includes a feature to download the generated summary as a PDF file.
- **Clean Interface:** User-friendly dashboard for inputting text and viewing results side-by-side.

## Tech Stack
- **Core Language:** Python.
- **NLP Libraries:** NLTK (Natural Language Toolkit), Scikit-learn.
- **Web Framework:** Flask / Python Web.
- **Frontend:** HTML5, CSS3.

## How It Works (Algorithm)
The system follows a standard extractive pipeline:
1.  **Preprocessing:** Tokenizing text into sentences and words, removing stop words.
2.  **Word Frequency Analysis:** Calculating the weight of each word in the document.
3.  **Sentence Scoring:** Assigning scores to sentences based on the presence of high-frequency keywords.
4.  **Extraction:** Selecting the top N sentences with the highest scores to form the summary.

## Screenshots
(اسحب الصورة اللي فيها التلخيص وارميها هنا تحت السطر ده)![News Summarization](https://github.com/user-attachments/assets/e1b0c6e3-1e6b-422f-90e8-00f1d68d0b96)
