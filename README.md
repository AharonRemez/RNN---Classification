# Sentiment Analysis of Movie Reviews Using Recurrent Neural Networks (RNN)
This project implements a Recurrent Neural Network (RNN) using Long Short-Term Memory (LSTM) layers to classify movie reviews as positive or negative. The model was trained on the Kaggle dataset: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), which contains 50,000 movie reviews labeled by sentiment.

## Project Overview
The goal of this project is to perform sentiment analysis on movie reviews using deep learning techniques. The RNN architecture, comprising two LSTM layers with 64 and 32 neurons respectively, was trained to accurately predict the sentiment expressed in movie reviews. This project can be extended for applications such as recommendation systems, customer feedback analysis, and real-time sentiment monitoring.

## Model Performance
- **Training Accuracy:** 97.72%
- **Training Loss:** 0.0655
- **Validation Accuracy:** 77.73%
- **Validation Loss:** 0.9245
#### Sample Prediction:
- **Text**: The movie by GeeksforGeeks was so good and the animation are so dope. I would recommend my friends to watch it.
- **Result**: **The review is positive**

## Dataset
The dataset used for training the model is available on Kaggle: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). It consists of 50,000 movie reviews from IMDB, labeled as positive or negative.

- To download the dataset, use the following command in your **terminal**:
```python
pip install kaggle
kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
unzip imdb-dataset-of-50k-movie-reviews.zip
```
Or in Google Colab:
```python
!pip install kaggle
!kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
!unzip imdb-dataset-of-50k-movie-reviews.zip
```

## Model Architecture
### The model architecture consists of:

- **First LSTM Layer:** 64 neurons 
- **Second LSTM Layer:** 32 neurons
