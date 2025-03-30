## 📌 About The Project

The Sentiment Classification System leverages machine learning and deep learning to analyze sentiments in Apple-related tweets. The project applies Natural Language Processing (NLP) to assess public opinion trends.

### 🏆 Key Features

* Sentiment classification using Logistic Regression, XGBoost, LSTM, CNN, and a Stacked Model.

* Data preprocessing with tokenization, stopword removal, and vectorization.

* Evaluation using Accuracy, Precision, Recall, and F1-score.

* Fine-tuned deep learning models for optimized performance.
  

### 🚀 Built With

* Python, Scikit-learn, TensorFlow/Keras, Transformers (Hugging Face) Pandas, NumPy, NLTK, and SpaCy


### ⚡ Getting Started

#### Prerequisites

Ensure Python is installed:

```bash 
python --version
 ```

Install required dependencies:

```bash
pip install -r requirements.txt
 ```

Installation


Clone the repository:

```bash
 git clone https://github.com/BetsyGitije/Apple-Sentiment-Analysis.git
 ```
Navigate to the project directory:

```bash
cd Apple-Sentiment-Analysis
```

Run the notebook or script:

```bash
jupyter notebook
```

### Usage
Run the sentiment analysis script:

```bash
python src/sentiment_analysis.py
```

Provide a dataset of tweets, and the model will classify sentiment.

### 📊 Model Performance

***Best Performing Model: Stacked Model with Class Weights***

* Achieved 75% accuracy.

* Strong recall for class '3' (largest class), ensuring effective classification.

* Balanced performance across Precision, Recall, and F1-score.

### 🔍 Key Insights

* Sentiment Distribution: Most tweets are Neutral (55%), followed by Negative (31%) and Positive (11%).

* Frequent Words: Positive sentiments contain words like "great" and "love," while negative tweets include "fix" and "suck."

### 📌 Recommendations

* Address recurring negative themes to enhance brand perception.

* Use positive feedback for marketing strategies.

* Improve accuracy by integrating external metadata and refining preprocessing techniques.

* Benchmark with competitors to identify differentiation opportunities

  







