# Sentiment_Analysis
Sentiment Analysis with Word2Vec and GloVe

# Sentiment Analysis with Word2Vec and GloVe

## Description

This Jupyter notebook explores the use of Word2Vec and GloVe word embeddings in sentiment analysis. It demonstrates how these pre-trained embeddings can be leveraged to improve the performance of machine learning models in classifying sentiment in text data. The notebook covers the following key steps:

- Preprocessing text data for embedding models.
- Loading and using pre-trained Word2Vec and GloVe embeddings.
- Building and training sentiment analysis models using these embeddings.
- Comparing the performance of models using different embeddings.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/vampokala/Sentiment_Analysis.git
    cd Sentiment_Analysis
    ```

2. **Create and Activate a Virtual Environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Download Necessary Embeddings**:
    - Word2Vec: Available from the [Google News pre-trained embeddings](https://code.google.com/archive/p/word2vec/).
    - GloVe: Available from the [GloVe website](https://nlp.stanford.edu/projects/glove/).

## Usage

To run the notebook, follow these steps:

1. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2. **Open `Word2Vec_GloVe_SentimentAnalysis.ipynb`** and run the cells sequentially.

Make sure you have downloaded the Word2Vec and GloVe embeddings and placed them in the specified directory before running the notebook.

## Data

The notebook uses a sentiment analysis dataset which you can obtain from the following sources:

- [Kaggle Sentiment Analysis Datasets](https://www.kaggle.com/datasets)
- Custom datasets can be loaded as long as they are preprocessed into the required format (text and label).

## Dependencies

The notebook requires the following Python libraries:
- `numpy`
- `pandas`
- `nltk`
- `gensim`
- `scikit-learn`
- `tensorflow` or `pytorch` (depending on the implementation used)

These can be installed via `pip` as shown in the setup instructions.

## Results

The notebook provides a comparative analysis of the performance of models using Word2Vec and GloVe embeddings for sentiment analysis. The results section includes:

- Evaluation metrics like accuracy, precision, recall, and F1-score.
- Visualizations of model performance and embeddings.

## Conclusion

By leveraging pre-trained word embeddings such as Word2Vec and GloVe, the notebook demonstrates improved sentiment analysis performance. It also highlights the nuances of using different embeddings and their impact on the classification results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
