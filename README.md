# Emotion Detection from Tweets using SVM

This project involves building a machine learning model to classify emotions expressed in English-language tweets using **Support Vector Machines (SVM)**. The dataset consists of Twitter messages, each labeled with one of six basic emotions: **anger**, **fear**, **joy**, **love**, **sad**, and **surprise**.

## Project Goals

- Preprocess tweet data (cleaning, tokenization, vectorization).
- Train an SVM classifier to predict the emotion associated with a tweet.
- Compare different SVM kernel functions (**linear**, **polynomial**, **RBF**, etc.) to determine which provides the best performance.
- Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project can be found on Kaggle:

🔗 **[Emotions Dataset – Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/emotions-dataset)**

> **Note:** Due to GitHub file size limitations, the dataset is not included in this repository.  
> Please download the dataset from the link above and place the CSV file (`emotions.csv`) in the project root directory.

**Sample Format:**

| text                            | emotion   |
|----------------------------------|-----------|
| i feel awesome                   | joy       |
| this is the worst day of my life | sad   |
| i am so scared                   | fear      |

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/emotion-svm.git
   cd emotion-svm
