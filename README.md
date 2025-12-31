# Named Entity Recognition & Disambiguation

A Deep learning–powered Named Entity Recognition (NER) system designed to identify, classify, and disambiguate entities in natural language text. Built using state-of-the-art NLP models, it supports extracting structured information from unstructured data with high accuracy.

## 🚀 Features

- 🔠 **Text Preprocessing Pipeline**: Lowercasing, punctuation removal, tokenization, lemmatization, and stopword removal for clean and normalized input text.
- 📚 **POS and NER Tag Handling**: Parses and processes part-of-speech and entity tags from stringified list formats.
- 🔢 **Tokenization & Padding**: Uses TensorFlow/Keras tokenizers for converting text and tags into sequences and ensures consistent input shape with padding.
- 🧠 **BiLSTM Architecture**: A powerful deep learning model combining bidirectional LSTMs with dropout for robust NER performance.
- 🔄 **Custom Training Loop**: Includes early stopping and learning rate scheduling for better convergence and generalization.
- 💾 **Model Saving & Loading**: Save and reload trained models and tokenizers for future inference.
- 📈 **Evaluation & Prediction**: Predict named entities in raw sentences and map predictions back to human-readable tags.
- 🧪 **Pretrained Inference Demo**: Easily test the model on new sentences with a single function call.

## ⚙️ Tech Stack

- **Python 3.10**
- **TensorFlow / Keras**
- **NLTK for text processing**
- **NumPy, Pandas**
- **Preprocessed input with POS + IOB Tag formats**

## 📝 License © [Praharsha Surampudi](https://www.linkedin.com/in/praharsha-surampudi/)
