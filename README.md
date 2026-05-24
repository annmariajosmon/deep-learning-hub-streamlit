# Deep Learning Hub - Streamlit AI Application

## Overview

Deep Learning Hub is a centralized Streamlit-based AI application designed to host and deploy multiple Deep Learning and Natural Language Processing (NLP) models through an interactive web interface.

The project integrates multiple neural network architectures including DNN, RNN, LSTM, CNN, and Perceptron-based models for prediction and text analysis tasks.

---

## Features

- Multi-model AI deployment using Streamlit
- Deep Learning model integration
- NLP text preprocessing and prediction
- Support for DNN, RNN, LSTM, CNN architectures
- Tokenizer serialization and loading
- Interactive web-based prediction interface
- Modular AI application structure

---

## Technologies Used

- Python
- Streamlit
- TensorFlow
- Keras
- NumPy
- Pickle
- Deep Learning
- NLP

---

## Implemented Models

- Perceptron Model
- Backpropagation Neural Network
- Deep Neural Network (DNN)
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Convolutional Neural Network (CNN)

---

## Project Architecture

```text
User Input
    ↓
Streamlit Web Interface
    ↓
Tokenizer & Preprocessing
    ↓
Deep Learning Models
    ↓
Prediction Output
```

---

## Repository Structure

```text
Deep-Learning-Hub/
│
├── README.md
├── requirements.txt
│
├── apps/
│   ├── app.py
│
├── models/
│   ├── dnn_model.pkl
│   ├── rnn_model.pkl
│   ├── lstm_model.pkl
│
├── tokenizers/
│   ├── dnn_tokenizer.pkl
│   ├── rnn_tokenizer.pkl
│   └── lstm_tokenizer.pkl
│
└── notebooks/
```

---

## Installation

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## Run the Streamlit Application

```bash
streamlit run app.py
```

---

## Applications

- NLP text classification
- Deep learning model deployment
- AI-powered web applications
- Sentiment analysis systems
- Educational AI demonstrations

---

## Future Improvements

- Docker deployment
- Cloud hosting
- Transformer model integration
- Real-time API deployment
- Multi-user authentication

---

## Author

ANN MARIA JOSMON
