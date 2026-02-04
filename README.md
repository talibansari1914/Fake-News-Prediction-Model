# Fake News Prediction System using Machine Learning

## 📌 Project Overview
This project is an end-to-end **Machine Learning based Fake News Detection System** that classifies news articles as **Real** or **Fake** using Natural Language Processing (NLP) techniques.<br>
With the rapid spread of misinformation on digital platforms, automated fake news detection plays a critical role in ensuring information authenticity.<br>

---

## 🎯 Problem Statement
To build a predictive model that can accurately identify whether a news article is **Real (0)** or **Fake (1)** based on textual information.<br>

---

## 📊 Dataset Description
The dataset contains the following features:<br>

| Column Name | Description |<br>
|------------|-------------|<br>
| id | Unique identifier |<br>
| title | News headline |<br>
| author | Author of the article |<br>
| text | Full news article |<br>
| label | Target variable (0 = Real, 1 = Fake) |<br>

---

## 🛠️ Technologies & Tools Used
- **Programming Language:** Python  <br>
- **Libraries:**<br>
  - NumPy<br>
  - Pandas<br>
  - NLTK<br>
  - Scikit-learn<br>
  - Regular Expressions (re)<br>

---

## 🔄 Data Preprocessing Steps
1. Handling missing values<br>
2. Merging `author` and `title` columns for richer text representation<br>
3. Text cleaning:<br>
   - Removal of special characters<br>
   - Lowercasing<br>
   - Stopwords removal<br>
   - Stemming using **Porter Stemmer**<br>

---

## 🧠 Feature Extraction
- **TF-IDF Vectorization**<br>
  - Converts textual data into numerical format<br>
  - Assigns higher weight to informative words<br>
  - Reduces impact of commonly used words<br>

---

## 🤖 Model Used
- **Logistic Regression**<br>
  - Suitable for binary classification<br>
  - Fast and interpretable<br>
  - Widely used in text classification problems<br>

---

## 📈 Model Training & Evaluation
- Data split:<br>
  - 80% Training<br>
  - 20% Testing<br>
- Evaluation Metric:
  - **Accuracy Score**<br>

The model shows strong performance with comparable training and testing accuracy, indicating good generalization.<br>

---

## 🔮 Prediction System
The trained model can predict the authenticity of unseen news articles and outputs:<br>
- **"The News is Real"**<br>
- **"The News is Fake"**<br>

---

## 🚀 Project Workflow
1. Data Loading<br>
2. Data Cleaning & Preprocessing<br>
3. Feature Engineering<br>
4. Text Vectorization<br>
5. Model Training<br>
6. Model Evaluation<br>
7. Prediction on New Data<br>

---

## 📌 Key Highlights
- Real-world NLP application<br>
- Industry-standard preprocessing pipeline<br>
- Efficient and scalable ML model<br>
- Ready for deployment and extension<br>

---

## 🔮 Future Improvements
- Use advanced models like Naive Bayes, SVM, or LSTM<br>
- Hyperparameter tuning<br>
- Model deployment using Flask or FastAPI<br>
- Integration with web or mobile applications<br>

---

## 👤 Author
**Abbu Talib Ansari**<br>
GiHub:https://github.com/talibansari1914/Fake-News-Prediction<br>
---

## 📄 License
This project is open-source and available for educational and learning purposes.<br>
