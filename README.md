# Next Word Prediction (LSTM)

An NLP project that predicts the probable next word from a given text sequence, using an LSTM model.

## What is in this repo
- `RNN.ipynb` — model training notebook
- `app.py` — Streamlit app for interactive use
- `lstm_model.h5` — trained LSTM model
- `tokenizer.pkl` and `max_len.pkl` — tokenizer and sequence length used by the model
- `qoute_dataset.csv` — dataset file as uploaded (spelling as in the original file)

## How to run
1. Install Python dependencies for TensorFlow / Keras and Streamlit.
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
3. Enter a text sequence and view the predicted next words.

## Results
To be added after re-running the notebook: test-set accuracy, dataset size, and a baseline comparison. No accuracy figure is claimed here until that run is verified.

## Tech
Python, TensorFlow / Keras, LSTM, Streamlit
