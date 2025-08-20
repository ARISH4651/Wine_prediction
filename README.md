# 🍷 Wine Quality Prediction

This project predicts whether a wine is of **good** or **bad quality** based on its physicochemical properties using **Machine Learning**.

---

## 📌 Project Workflow
1. **Data Analysis & Visualization**
   - Explored wine quality distribution
   - Analyzed correlations between features (alcohol, acidity, sulphates, etc.)
   - Visualized feature distributions and their impact on quality

2. **Data Preprocessing**
   - Converted `quality` scores (0–10) into binary classes:  
     - Good Quality (1)  
     - Bad Quality (0)
   - Split data into features (X) and target (y)

3. **Model Building**
   - Used **Random Forest Classifier**
   - Trained on 80% of the dataset, tested on 20%

4. **Model Evaluation**
   - Training Accuracy: ~100%  
   - Testing Accuracy: ~92%  
   - Custom input testing for new wine samples

---

## 📊 Future Improvements
- Compare with Logistic Regression, Gradient Boosting, and SVM  
- Use advanced metrics (Confusion Matrix, Precision, Recall, F1-score)  
- Add feature importance visualization  
- Deploy the model using Flask or Streamlit  

---

## 📦 Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
