
# 🧠 NLP Sentiment Analysis – IMDb Movie Reviews

This project applies Natural Language Processing (NLP) techniques to classify movie reviews from the IMDb dataset as **positive** or **negative** using a Naive Bayes model.

---

## 📌 Project Structure

```
nlp-sentiment-analysis-imdb/
│
├── data/                    # Raw dataset (IMDb reviews)
├── notebooks/               # Jupyter Notebooks for EDA and modeling
├── src/                     # Source code: preprocessing, model, utils
├── outputs/                 # Trained model, vectorizer, and evaluation results
├── reports/                 # Visualizations and EDA charts
├── requirements.txt         # List of Python dependencies
├── README.md                # Project documentation
└── .gitignore               # Ignored files (e.g. checkpoints)
```

---

## 🎯 Objective

To build a binary text classification model that can predict whether a movie review is **positive** or **negative** based on its content.

---

## 📊 Dataset

- **Source**: [IMDb Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Size**: 50,000 labeled movie reviews
- **Labels**: `positive`, `negative`

---

## 🧪 Tools & Libraries

- **Data Handling**: `pandas`, `numpy`
- **Text Processing**: `nltk`, `re`
- **Modeling**: `scikit-learn` (TF-IDF, Naive Bayes)
- **Evaluation**: `classification_report`, `confusion_matrix`
- **Saving Models**: `pickle`

---

## 🔁 Workflow

1. **Data Loading**
2. **Text Cleaning**: Remove HTML, non-letters, lowercase, remove stopwords, stemming.
3. **Feature Extraction**: TF-IDF vectorization (top 5000 words).
4. **Modeling**: Multinomial Naive Bayes.
5. **Evaluation**: Classification metrics and confusion matrix.
6. **Saving**: Model and vectorizer saved for future use.

---

## 📈 Results

The trained Naive Bayes model achieved good performance on the test data. Full results are saved in the `outputs/` folder.

---

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook notebooks/eda_and_modeling.ipynb
```

---

## 👤 Author

**Hamri Rym**  
NLP & ML Enthusiast  
📧 [Add your email or LinkedIn here]

---

## 📌 License

This project is open-source for educational purposes.
