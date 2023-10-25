**Project Title: Sentiment Analysis with BERT on Google Play Store App Reviews**

**Description:**

Welcome to the GitHub repository for our Sentiment Analysis project, where we leverage cutting-edge Natural Language Processing (NLP) techniques, powered by PyTorch and Transformers, to analyze sentiments in Google Play Store app reviews. This project not only provides valuable insights into user sentiment but also demonstrates the power of state-of-the-art BERT models for multi-class classification.

**Key Highlights:**

- **Data Collection:** We collected a comprehensive dataset of Google Play Store app reviews using the "google-play-scraper." These reviews were further categorized into negative, neutral, and positive sentiments based on the corresponding 1 to 5 scale ratings, providing a rich source of labeled data for analysis.

- **BERT as Encoder:** For the core of our sentiment analysis task, we employed the BERT base cased NLP model as an encoder. This state-of-the-art model is known for its exceptional performance in understanding context and semantics in text data.

- **Multi-class Classification:** We constructed a multi-class classification model by mounting a classification head on top of the BERT encoder. This allowed us to classify reviews into multiple sentiment categories, enabling us to capture the nuanced sentiment expressed by users.

- **Model Selection:** To ensure the robustness and accuracy of our sentiment analysis, we trained multiple iterations of the model and selected the one with the highest validation accuracy. This careful selection process guarantees the reliability of our sentiment predictions.

This repository serves as a valuable resource for NLP enthusiasts, data scientists, and anyone interested in sentiment analysis. The documented code and analysis showcase how to harness the power of BERT-based models to gain insights from user reviews and make informed decisions in the context of app development and user satisfaction.

**Keywords:** Sentiment Analysis, BERT, Natural Language Processing, PyTorch, Transformers, Google Play Store, App Reviews, Multi-class Classification, Data Analysis.
