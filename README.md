# IMDB Sentiment Analysis

- Classify IMDB movie reviews as positive or negative using deep learning.
- Loaded zipped CSV from Google Drive into Pandas DataFrame.
- Explored: Balanced positive/negative reviews.
- Preprocessed: Tokenized text (`TextVectorization`), encoded labels (`LabelEncoder`).
- Models:
  - ANN: Dense layer (ReLU), dropout, sigmoid output; low test accuracy.
  - Bidirectional LSTM: One-hot inputs, LSTM, dropout, sigmoid output; high test accuracy.
- Evaluated: Saved best models (`ModelCheckpoint`), compared accuracies.
- Insight: LSTM outperformed ANN for text context.

## Google Colab Notebook
[Google Colab Notebook](https://colab.research.google.com/drive/15bJ3G0Q9xRWHBXolrJ4wSnQ98TR_aBvA?usp=sharing)
