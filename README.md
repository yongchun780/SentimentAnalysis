# Sentiment Analysis Notebook

This Jupyter notebook provides a Python implementation for performing sentiment analysis on textual data. It is designed to analyze the sentiment of input texts, classifying them into positive, negative, or neutral categories.

## Team members:
Yongchun Chen
Zhuochen Dai

## Getting Started

### Prerequisites

Before running this notebook, ensure you have the following packages installed:

- `nltk`: A leading platform for building Python programs to work with human language data.
- `vader_lexicon`: A lexicon resource used by the NLTK SentimentIntensityAnalyzer for sentiment analysis.

You can install these packages using pip:

```bash
pip install nltk
nltk.download('vader_lexicon')
```

### Running the Notebook

To run this notebook, you will need Jupyter Notebook or JupyterLab installed on your system. If you do not have Jupyter installed, you can install it using pip:

```bash
pip install notebook  # For Jupyter Notebook
pip install jupyterlab  # For JupyterLab
```

After installing, navigate to the notebook directory in your terminal and run:

```bash
jupyter notebook  # For Jupyter Notebook
# or
jupyter lab  # For JupyterLab
```

Open `sentimentAnalysis.ipynb` and execute the cells sequentially to perform sentiment analysis.

## How It Works

This notebook implements sentiment analysis using the NLTK library. It processes textual data, evaluates the sentiment expressed within, and classifies each text as positive, negative, or neutral based on predefined criteria.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests if you have ideas for improvements or additions to the sentiment analysis process.

## License

This project is open source and available under [INSERT LICENSE HERE].
