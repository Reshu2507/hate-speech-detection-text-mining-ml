# Hate Speech Detection using Text Mining and Machine Learning

This project focuses on detecting hate speech in user-generated text using text mining techniques and machine learning models. The objective is to classify comments as toxic or non-toxic based on their content.
The system uses TF-IDF for feature extraction and Logistic Regression as the primary classification model, along with comparisons against Naive Bayes and Support Vector Machine (SVM).

## Dataset

* **Dataset Used:** Jigsaw Toxic Comment Classification Dataset
* **Features:**

  * `comment_text` → Input text
  * `toxic` → Target label (0 = non-toxic, 1 = toxic)

## Methodology

### 1. Data Preprocessing

* Lowercasing text
* Removing URLs, punctuation, and special characters
* Stopword removal
* Lemmatization

### 2. Text Mining & Analysis

* Class distribution analysis
* Comment length distribution
* Word frequency analysis
* Filtered word cloud visualization

### 3. Feature Extraction

* TF-IDF Vectorization
* N-grams (unigrams + bigrams)

### 4. Model Training

* Logistic Regression (primary model)
* Naive Bayes
* Support Vector Machine (SVM)

### 5. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

## Results

* Logistic Regression achieved the best overall performance
* Balanced performance across all evaluation metrics
* Effective in handling high-dimensional text data

## Visualizations

* Class Distribution
* Comment Length Distribution
* Word Frequency Analysis
* Word Cloud (Filtered)
* Model Performance Comparison
* Confusion Matrix

  
## Key Insights

* Toxic comments are generally shorter and more direct
* TF-IDF effectively captures important textual features
* Logistic Regression provides a strong and interpretable baseline


## Conclusion

This project demonstrates that traditional machine learning approaches combined with text mining techniques can effectively detect hate speech. While advanced deep learning models offer improved performance, simpler models like Logistic Regression provide a strong balance between accuracy, efficiency, and interpretability.


