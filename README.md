# Fake-News-Detection

#📰 Fake News Detection
This project is focused on detecting fake news articles using machine learning and natural language processing techniques. It classifies news as real or fake based on textual content.

<br>
##📌 Project Summary
Fake news is a serious threat to public trust and information integrity. In this project, we build and evaluate multiple machine learning models to classify news articles accurately. The models are trained on real-world data and evaluated using accuracy, precision, and recall.

<br>
##📂 Dataset
The project uses two datasets:

True.csv: Contains real news articles.

Fake.csv: Contains fake news articles.

Each dataset includes:

title: Headline of the article

text: Full text of the article

subject: Category of news (e.g., politics, world news)

date: Publication date

A new column class is added for labeling:

1 = Real news

0 = Fake news

<br>
🧰 Libraries Used
Pandas – for data manipulation

NumPy – for numerical operations

NLTK – for text preprocessing and stopwords

Scikit-learn – for machine learning models and vectorization

Matplotlib & Seaborn – for data visualization

WordCloud – for generating word clouds

<br>
🧪 IDE
Jupyter Notebook

<br>
🛠️ Preprocessing Steps
Combined real and fake datasets

Removed punctuation, stopwords, and special characters

Created a content column combining title and text

Vectorized the text using TF-IDF

Split the dataset into train/test

<br>
🤖 Models Trained
Logistic Regression

Multinomial Naive Bayes

Support Vector Machine (Linear SVC)

Random Forest Classifier

Gradient Boosting Classifier

Each model was evaluated on the test set and also tested against manually selected samples.

<br>
📈 Evaluation
Performance was assessed using:

Accuracy Score

Confusion Matrix

Manual Predictions

<br>
🏁 Final Output
The best-performing models successfully identified fake news with high accuracy. The project also includes a manual sample test to demonstrate real-world application.
