
# 📘 Social Media Sentiment Analysis

This project performs sentiment analysis on social media text data using traditional Natural Language Processing (NLP) and machine learning techniques in Python. It includes data loading, preprocessing, visualization, model training, and evaluation — all in a clean Jupyter Notebook format.

---

## 📂 Project Structure

```
📁 sentiment-analysis/
├── Social Media Sentiment Analysis.ipynb
├── sentimentdataset.csv
└── README.md
```

---

## 📊 Dataset

- **File**: `sentimentdataset.csv`
- **Columns**:
  - `text`: The text content from social media (tweets/posts).
  - `sentiment`: The sentiment label (e.g., `positive`, `negative`, `neutral`).

---

## ✅ Features Implemented

### 🔍 1. Data Loading & Inspection
- Load CSV using Pandas
- Check for missing values
- Explore class balance

### 🧼 2. Data Cleaning
- Remove nulls
- Lowercase text
- Remove punctuation, URLs, and extra spaces

### 📊 3. Exploratory Data Analysis (EDA)
- Sentiment distribution
- Word count & text length analysis
- WordCloud visualizations for sentiment

### ⚙️ 4. Preprocessing
- Cleaned `text` into `clean_text`
- Added `text_length` column
- Vectorized text using `CountVectorizer`

### 🤖 5. Model Training
- Model: Naive Bayes (`MultinomialNB`)
- Split: 80% train, 20% test
- Evaluation: Accuracy, Precision, Recall, F1-score

### 📉 6. Evaluation
- Classification report
- Accuracy score

---

## 🛠️ Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
```

Or use the provided notebook in a Jupyter environment.

---

## ▶️ How to Run

1. Clone this repo or download the `.ipynb` and `sentimentdataset.csv` files.
2. Open `Social Media Sentiment Analysis.ipynb` in **Jupyter Notebook** or **VSCode (Jupyter Extension)**.
3. Execute each cell step-by-step.
4. Optionally modify the model or preprocessing as needed.

---

## 📈 Sample Results

- **Accuracy Achieved**: ~80-90% depending on data and preprocessing.
- **Model Used**: Naive Bayes (Multinomial)
- **Visuals**:
  - Word clouds for sentiments
  - Histogram of text lengths
  - Count plot of sentiment distribution

---

## 🚀 Future Improvements

- Use TF-IDF vectorization
- Implement LSTM or BERT for better accuracy
- Build a Streamlit app for UI
- Add more language support

---

## 📌 Credits

- Built using Python, Pandas, Scikit-learn, Seaborn, WordCloud, and Matplotlib.
- Dataset provided in `sentimentdataset.csv`.
