✈️ Airline Tweet Sentiment Analysis using LSTM (Keras)
This project is a sentiment classification model that predicts whether a tweet about an airline is positive or negative using deep learning. It leverages LSTM networks and Keras for sequence modeling on real-world tweet data.

📁 Dataset
Source: Tweets.csv
Columns used:
text: The actual tweet
airline_sentiment: The sentiment label (positive, neutral, negative)
➡️ Neutral tweets are removed to simplify the task to binary classification.

🛠️ Technologies Used
Python
Pandas, NumPy
TensorFlow / Keras
LSTM Neural Networks
Tokenizer & Padding
Matplotlib for Visualization
Google Colab
GitHub
Pickle (for saving tokenizer)
📊 Model Architecture
Embedding Layer: Converts words to dense vectors
SpatialDropout1D: Adds regularization
LSTM Layer: Learns sequence dependencies
Dense Layer: Sigmoid activation for binary output
