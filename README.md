# Covid-19-Sentiment-Analysis-using-fastText

## Dataset

In this project the Covid 19 tweet dataset is used. It consist of 3090 samples with sentiment labels.

The dataset has 4 sentiment labels: 'Fear', 'Anger', 'Joy', 'Sad’. The value count of each sentiment is as follows:

| Sentiment | Count |
| :---: | :---: |
| Fear | 801 |
| Sad |	795 |
| Joy |	727 |
| Anger | 767 |

# Building the model

1. First an inital exploration of the dataset is done.
2. A feature set of useful features are generated (optional)
3. Data is preprocessed to remove unwanted characters.
4. Loading the fastText library
5. Splitting the data into train and test datasets
6. Creating the model and testing with custom input
7. Creating the model with Ngrams and testing
