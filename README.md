# BBC News Classification with Markov Chains

This project classifies BBC News articles into five categories — **economics**, **education**, **politics**, **sports**, and **entertainment** — using a **Markov Chain-based language model**.

---

## ✨ Features
- ✅ **Text preprocessing** with NLTK (tokenization, stopword removal, lemmatization)
- ✅ **Markov Chain models** trained separately for each category
- ✅ **TF-IDF baseline** with Logistic Regression for comparison
- ✅ **Stratified train/test split** to maintain class balance
- ✅ **Confusion Matrix heatmap** for model evaluation

---

## 🧠 What is a Markov Chain in this project?
A **Markov Chain** treats each word as a state and learns the transition probabilities between words.  
When predicting a category for a new article, we select the category whose Markov Chain most plausibly “generates” the article's text.

---

