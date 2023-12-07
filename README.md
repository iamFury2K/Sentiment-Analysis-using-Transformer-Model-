# CineBERT: Cinematic Sentiment Analysis with DistilBERT

CineBERT is a sentiment analysis project tailored for IMDb movie reviews, powered by DistilBERT - a cutting-edge, distilled version of BERT. Dive into this powerful Natural Language Processing (NLP) journey to unravel the sentiments behind cinematic narratives!

## Overview

CineBERT utilizes the DistilBERT model to conduct sentiment analysis on IMDb movie reviews. Through transfer learning and fine-tuning, this project deciphers audience sentiments, providing insights into the emotional resonance of movies among viewers.

## Setup

### Requirements

Ensure you have Python installed, along with the following libraries:

- `pandas`
- `requests`
- `torch`
- `transformers`

### Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/iamFury2K/cinebert-sentiment-analysis.git
    cd cinebert-sentiment-analysis
    ```

2. Obtain and preprocess the dataset:

    ```bash
    python data_preparation.py
    ```

3. Train and evaluate the CineBERT model:

    ```bash
    python train_evaluate.py
    ```

## Project Structure

- `data_preparation.py`: Downloads and preprocesses the IMDb movie review dataset.
- `train_evaluate.py`: Defines, trains, and evaluates the DistilBERT-based CineBERT model.
- `movie_data.csv`: Preprocessed movie review dataset.

## Evaluation Metrics

- **Accuracy:** Measures the model's correctness in predicting sentiments.
- **Loss:** Indicates the model's performance during training.

## Results

After training, the model's performance can be observed in the console logs and stored in the `./results` directory.

## Acknowledgments

This project harnesses the `transformers` library by Hugging Face for leveraging pre-trained language models.

## Contributions

Contributions and feedback are welcome! Feel free to open an issue or pull request.

## License

This project is licensed under the [MIT License](LICENSE).

