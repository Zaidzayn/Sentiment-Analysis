# 📊 Sentiment Analysis on Kindle Reviews

This project performs **Sentiment Analysis** on a dataset of Kindle product reviews.  
Using Natural Language Processing (NLP) techniques, the model predicts whether a review is **positive, negative, or neutral** based on its text.

---

## 📁 Project Structure
Sentiment-Analysis/
│
├── all_kindle_review.csv # Dataset containing Kindle product reviews
├── kindl_review.ipynb # Jupyter Notebook for sentiment analysis
└── README.md # Project 


---

## 📌 Features
- **Data Loading & Cleaning**: Handles missing values and cleans text for better analysis.
- **Exploratory Data Analysis (EDA)**: Visualizes rating and sentiment distributions.
- **Text Preprocessing**:
  - Lowercasing
  - Removing punctuation & stopwords
  - Tokenization
- **Model Building**:
  - Vectorization using Bag-of-Words or TF-IDF
  - Classification using Machine Learning models
- **Evaluation**:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix

---

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data manipulation)
- **Matplotlib, Seaborn** (Visualization)
- **NLTK / spaCy** (Text preprocessing)
- **Scikit-learn** (ML models & evaluation)

---

## 📊 Dataset
The dataset `all_kindle_review.csv` contains:
- **Review Text** – The written feedback from customers.
- **Ratings** – Star ratings (e.g., 1 to 5).
- **Additional fields** – May include product details, review dates, etc.

---

## 🚀 How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/Zaidzayn/Sentiment-Analysis.git
   cd Sentiment-Analysis
