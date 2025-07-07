# 📰 Fake_News_Detection

This is a fake news detection system that uses Natural Language Processing (NLP) and a Logistic Regression model to classify news articles as **Real** or **Fake**. Built with Python, trained on labeled datasets, and ready to be scaled into an interactive web app.

---

## 📥 Dataset Download

This project uses the [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset).

Please download `Fake.csv` and `True.csv` manually and place them inside your directory.

## 🚀 Getting Started

### 1. Set up virtual environment

```
python -m venv venv
```
##On Windows:
```
venv\Scripts\activate
```

##On macOS/Linux:
```
source venv/bin/activate
```

##Install required packages
```
pip install -r requirements.txt
```

Run the Streamlit app
```
streamlit run app.py

```

## Model Details
### Algorithm: Logistic Regression

### Vectorizer: TF-IDF

### Datasets: Fake and True news datasets

### Goal: Detect fake news articles using textual analysis
