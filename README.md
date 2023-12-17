# Dual LSTM for POS Tagging-atis dataset

This project implements a dual LSTM (Long Short-Term Memory) neural network for part-of-speech tagging. The model utilizes both word embeddings and character-level embeddings to capture rich linguistic information. The training is performed on the UD (Universal Dependencies) English dataset.

## Project Structure

The project is structured into several components:

1. **Data Preparation:** Loading and parsing the UD English dataset in CoNLL-U format.

2. **Data Preprocessing:** Converting words, characters, and tags into numerical indices.

3. **Model Definition:** Defining the architecture of the dual LSTM tagger using PyTorch.

4. **Training:** Training the model on the prepared dataset.

5. **Inference:** Making predictions on new sentences using the trained model.

## Instructions to Run

Follow the steps below to run the project:

### 1. Clone the Repository

```bash
git clone github.com/vivek-r-2000/Dual-LSTM-for-POS-Tagging-atis-dataset.git
cd dual-lstm-tagger
```

### 2. Install Dependencies
Make sure you have Python installed. Create a virtual environment and install the required dependencies.

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

### 3. Download the Dataset
Download the UD English dataset in CoNLL-U format and place it in the Data directory.

### 4. Run the Jupyter Notebook
Run the jupyter notebook in your python environment

### 5. Input a Test Sentence
After training, the notebook will prompt you to enter a test sentence. Input a sentence, and the model will predict the part-of-speech tags for each word.

