BBC News Classification with Markov Chains
This project classifies BBC News articles into 5 categories — economics, education, politics, sports, and entertainment — using a Markov Chain-based language model.

✨ Features
✅ Text preprocessing with NLTK (tokenization, stopwords removal, lemmatization)
✅ Markov Chain models trained separately for each category
✅ TF-IDF baseline with Logistic Regression for comparison
✅ Stratified train/test split to maintain class balance
✅ Confusion Matrix heatmap for model evaluation

🧠 What is a Markov Chain in this project?
A Markov Chain treats each word as a state and learns transition probabilities between words.
During prediction, we choose the category whose Markov Chain most plausibly “generates” the test article.
