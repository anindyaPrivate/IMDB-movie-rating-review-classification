

# 🎬 IMDB Movie Review Sentiment Analysis

![IMDB](https://upload.wikimedia.org/wikipedia/commons/6/69/IMDB_Logo_2016.svg)

This project leverages a Simple RNN model to classify IMDB movie reviews as positive or negative. It includes a Streamlit web application where users can enter movie reviews and get real-time sentiment analysis.

## 🌟 Features

- **Real-time Sentiment Analysis**: Classify movie reviews as positive or negative.
- **Interactive Web App**: User-friendly interface powered by Streamlit.
- **Pretrained Model**: Uses a pretrained Simple RNN model for predictions.

## 🚀 Try the App

You can try the app by clicking the link below:

[**IMDB Movie Review Sentiment Analysis App**](https://imdb-movie-rating-review-classification-vmcywnxypwyiyfshmodct3.streamlit.app/)

## 🛠️ Installation

Follow these steps to run the project locally:

1. **Clone the repository**:
   ```bash
    git clone https://github.com/anindyaPrivate/IMDB-movie-rating-review-classifiaction.git

2. **Navigate to the project directory**:
```bash
cd your-repository

3. **Create and activate a virtual environment**:

    ```bash
    python -m venv .venv
    ```

    - **Windows**:
      ```bash
      .venv\Scripts\activate
      ```
      
    - **macOS/Linux**:
      ```bash
      source .venv/bin/activate
      ```


4.Install the dependencies:
pip install -r requirements.txt

5.Run the Streamlit app:
streamlit run main.py



📋 Usage
1.Enter a movie review: Type or paste a movie review into the text area.
2.Classify: Click the "Classify" button to see the sentiment classification.
3.View Results: The sentiment (Positive/Negative) and prediction score will be displayed.

🧰 Requirements
Python 3.9+
TensorFlow 2.16.1
Streamlit 1.4.0

📊 Model
The Simple RNN model used in this project is trained on the IMDB dataset and includes:

Embedding Layer: Converts words to dense vectors.
Simple RNN Layer: Processes the sequences of word vectors.

⭐️ Don't forget to star the repository if you find it useful!
Dense Layer: Outputs the final sentiment classification.
