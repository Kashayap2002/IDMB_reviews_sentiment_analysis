# **Sentiment Analysis - IMDb Reviews**

### **Overview**
This project aims to classify IMDb movie reviews as either *positive* or *negative* using various machine learning algorithms. The dataset consists of 50,000 reviews, equally distributed between positive and negative sentiments.

---

## **Steps and Methodology**

### **1. Data Preprocessing**
- Removed unwanted characters, punctuation, and numbers using Python's `re` library.
- Standardized text by converting all characters to lowercase.
- Applied text-cleaning functions to remove noise.

### **2. Exploratory Data Analysis (EDA)**
- Verified there were no missing values in the dataset.
- Ensured an equal balance of positive and negative reviews.
- Used **word clouds** to visualize the most frequent words in positive and negative reviews.

### **3. Data Splitting**
- Divided the dataset into training (80%) and testing (20%) subsets using `train_test_split`.

### **4. Feature Extraction**
- Utilized **TF-IDF Vectorization** to convert textual data into numerical form for machine learning models.

---

## **Models Implemented**

### **Logistic Regression**
- **Accuracy**: 89.77%
- **Precision**: 88.77%
- **Recall**: 90.50%
- **F1-Score**: 89.63

### **Naive Bayes**
- **Accuracy**: 86.15%
- **Precision**: 88.81%
- **Recall**: 84.23%
- **F1-Score**: 86.46

### **Decision Tree**
- **Accuracy**: 73.42%
- **Precision**: 65.76%
- **Recall**: 77.46%
- **F1-Score**: 71.13

### **K-Nearest Neighbors (KNN)**
- **Accuracy**: 74.65%
- **Precision**: 70.50%
- **Recall**: 76.70%
- **F1-Score**: 73.47

### **Linear Regression**
- Calculated **Mean Squared Error (MSE)**: 0.1828
- Linear regression is unsuitable for categorical predictions.

---

## **Performance Metrics**
- **Accuracy**: Proportion of correctly predicted reviews.
- **Precision**: Accuracy of positive sentiment predictions.
- **Recall**: Sensitivity to detecting positive reviews.
- **F1-Score**: Harmonic mean of precision and recall.

### **Confusion Matrices**
Generated for each model to analyze True Positives, True Negatives, False Positives, and False Negatives.

---

## **ROC Curve Analysis**
- Plotted **ROC Curves** for all models.
- **Logistic Regression** achieved the highest AUC (Area Under Curve), indicating its superiority.

---

## **Visualizations**
- **Word Clouds**: Visualized the most common words in positive and negative reviews.
- **ROC Curves**: Compared model performances graphically.

---

## **Conclusion**
- **Best Performing Model**: Logistic Regression.
- Logistic Regression had the highest accuracy, precision, recall, and F1-Score, making it the most effective algorithm for this task.
- Other models like Naive Bayes and Decision Tree also provided insights into text classification.

---

## **Challenges**
- Cleaning and preprocessing text data to enhance accuracy.
- Selecting the best evaluation metrics for model comparison.

---

## **Applications**
- Sentiment analysis can be applied in:
  - Customer feedback analysis.
  - Brand reputation monitoring.
  - Social media sentiment tracking.

---

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/Kashayap2002/IDMB_reviews_sentiment_analysis
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python sentiment_analysis.py
   ```
## **Authors**
- **Aakanksha Kashyap (21052466)**





