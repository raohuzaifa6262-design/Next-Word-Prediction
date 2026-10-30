# Next Word Prediction

A deep learning natural language model for predicting subsequent words in sequences using recurrent neural architectures (LSTM / RNN).

## Overview
This project trains and deploys an LSTM language model trained on text quotes to suggest the most likely next words given an input prefix prompt.

## Project Structure
- `app.py`: Streamlit / Flask web application for real-time text generation and next-word inference.
- `RNNimplementation.ipynb`: RNN and LSTM model exploration, architecture design, and training pipeline.
- `codefile.ipynb`: Data preparation and tokenization experiments.
- `lstm_model (1).h5`: Saved trained Keras LSTM neural network weights.
- `tokenizer.pkl`: Fitted text tokenizer and vocabulary index.
- `max_len.pkl`: Sequence length padding parameter.
- `qoute_dataset.csv`: Dataset used for training.

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/raohuzaifa6262-design/Next-Word-Prediction.git
   cd Next-Word-Prediction
   ```
2. Set up virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   # Windows:
   .venv\Scripts\activate
   # Linux/macOS:
   source .venv/bin/activate

   pip install tensorflow keras streamlit pandas numpy
   ```
3. Run the application:
   ```bash
   python app.py
   # or if Streamlit: streamlit run app.py
   ```
