# Wikipedia Text Classification Project

This project aims to classify English texts into two categories: geographic and non-geographic. The classification is performed using the Wikipedia API and implemented with Python, primarily relying on the NLTK library.
The Project is developed as part of the NLP course for a Master's degree in Artificial Intelligence at the University of Verona.

## Project Overview

The project follows a pipeline that includes data retrieval from Wikipedia, preprocessing of text, and training of two classification models: Naive Bayes and Logistic Regression. The goal is to attribute a given text to one of two classes based on its content.

## Technologies Used

- **Python:** The primary programming language used for implementation.
- **NLTK (Natural Language Toolkit):** Used for text processing, tokenization, stop word removal, stemming, and lemmatization.
- **Wikipedia API:** Accessed using the `wikipediaapi` library to retrieve text content.

## Project Structure

The project consists of the following main components:

1. **Data Retrieval:** Utilizes the Wikipedia API to fetch text content for a given subject and identifies keywords within the content.

2. **Text Processing:** Implements various preprocessing techniques, including tokenization, stop word removal, stemming, and lemmatization.

3. **Logistic Regression Classification:**
   - With Preprocessing: Logistic Regression classifier trained with TF-IDF vectors extracted from preprocessed text.
   - Without Preprocessing: Logistic Regression classifier trained with TF-IDF vectors extracted from raw text.

4. **Naive Bayes Classification:**
   - Bag of Words Approach: Naive Bayes classifier trained on raw text without preprocessing.
   - Snowball Stop Words and Porter Stemmer Approach: Naive Bayes classifier trained with Snowball stop words and Porter Stemmer preprocessing.

## License

This project is licensed under the [MIT License](LICENSE).
