# Named Entity Recognition using BiLSTM and GloVe Embeddings

## Overview

This project implements a deep learning-based Named Entity Recognition (NER) system using a Bidirectional Long Short-Term Memory (BiLSTM) network with pretrained GloVe embeddings. The model is trained to identify and classify named entities such as persons, locations, organizations, and miscellaneous entities from textual data.

The project demonstrates an end-to-end Natural Language Processing (NLP) pipeline including preprocessing, feature engineering, sequence modeling, model training, and evaluation.

---

## Features

* Deep learning-based Named Entity Recognition
* BiLSTM architecture for sequence labeling
* Pretrained GloVe word embeddings
* Data preprocessing and tokenization
* Sequence padding and label encoding
* Model evaluation and performance analysis
* Visualization of training metrics

---

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

---

## Project Architecture

```text
Text Data
   ↓
Preprocessing & Tokenization
   ↓
Word Embedding Layer (GloVe)
   ↓
BiLSTM Network
   ↓
Dense + Softmax Layer
   ↓
Named Entity Predictions
```

---

## Dataset

The model is trained on a Named Entity Recognition dataset containing annotated text sequences for entity extraction tasks.

Entities detected include:

* PER → Person
* LOC → Location
* ORG → Organization
* MISC → Miscellaneous

---

## Model Workflow

1. Data Cleaning and Preprocessing
2. Tokenization and Vocabulary Creation
3. Sequence Padding
4. Integration of GloVe Embeddings
5. Building the BiLSTM Model
6. Model Training and Validation
7. Performance Evaluation and Visualization

---

## Results

The model achieved strong sequence tagging performance on validation data with high accuracy in entity recognition tasks.

### Evaluation Metrics

* Accuracy: 94%+
* Efficient contextual entity extraction
* Improved sequence understanding using BiLSTM architecture

---

## Applications

* Information Extraction
* Resume Parsing
* Chatbots and Virtual Assistants
* Search and Recommendation Systems
* NLP-based Analytics
* Automated Document Processing

---

## Future Improvements

* Integration with Transformer-based models like BERT
* Hyperparameter optimization
* Deployment using FastAPI or Streamlit
* Real-time entity extraction API

---

## Author

Yashika Verma

## License

This project is intended for educational and research purposes.
