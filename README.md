# 🔍 Sentiment Analysis of Rare Elements in News Headlines

This project performs sentiment analysis on financial news headlines related to rare elements using Natural Language Processing (NLP) techniques. The goal is to classify the sentiment (Positive, Negative, Neutral) of headlines and understand how news sentiment can affect the market performance of rare elements.

---

## 📁 Project Structure

```
sentimentofrarelements.ipynb   # Main Jupyter Notebook with full pipeline
requirements.txt               # List of dependencies
README.md                      # Project overview and setup guide
```

---

## 🚀 Features

* Real-time scraping of financial news headlines using `newsapi`
* Text preprocessing and cleaning
* Sentiment labeling using TextBlob
* Model training using:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine
* Model evaluation using accuracy and confusion matrix
* Sentiment prediction for new/unseen headlines

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/sentimentofrarelements.git
cd sentimentofrarelements
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## 🧠 Usage

1. Run the notebook:

   * Open `sentimentofrarelements.ipynb` in Jupyter Notebook or Google Colab.
   * Execute each cell sequentially.

2. To test new headlines:

   * Replace the example headlines in the input cell with your own.
   * Run the prediction cell to see the sentiment.

---

## 📊 Example Output

| Headline                                       | Predicted Sentiment |
| ---------------------------------------------- | ------------------- |
| "Rare earth prices surge amid supply concerns" | Positive            |
| "Demand for rare metals declines in Q1"        | Negative            |

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* TextBlob
* Matplotlib / Seaborn
* NewsAPI

---

## 🧪 Future Work

* Use more advanced models like BERT or RoBERTa
* Integrate a live dashboard for sentiment tracking
* Analyze correlation with market prices of rare elements

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* [NewsAPI](https://newsapi.org/)
* [TextBlob](https://textblob.readthedocs.io/)
* Scikit-learn contributors
