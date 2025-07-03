
# 🌍 Air Quality Classification – Model Tuning & Evaluation

This project implements a full machine learning classification pipeline using real-world air quality data. It explores multiple algorithms, applies systematic hyperparameter tuning, and evaluates model performance using cross-validation and multiple metrics.

---

## 🔧 Tools & Technologies

- **Python**, **pandas**, **NumPy**
- **scikit-learn** (Logistic Regression, KNN, Random Forest)
- **GridSearchCV**, **RandomizedSearchCV**
- **matplotlib**, **seaborn**
- **joblib** (model persistence)

---

## 📈 What’s Included

- Data loading and preprocessing  
- Training multiple models (`LogisticRegression`, `RandomForestClassifier`, `KNeighborsClassifier`)  
- Hyperparameter tuning using `GridSearchCV` and `RandomizedSearchCV`  
- Cross-validation results with mean and std reporting  
- Model performance comparison using accuracy and F1-score  
- Confusion matrix visualization (Seaborn heatmap)  
- Final model selection and export using `joblib`  
- Sample inference with saved model  

---

## 📊 Results

The final selected model was **Logistic Regression** tuned with GridSearchCV, offering the best trade-off between performance and interpretability.

---

## 🚀 How to Run

1. Clone the repo  
2. Make sure the dataset file (e.g., `AQI_Data.csv`) is available  
3. Run the notebook `main_file.ipynb` step by step  
4. The final model will be saved as `final_model.pkl`  

---

## 📁 Example Output

- Confusion matrix plot  
- Classification report  
- Model accuracy comparison chart  

---

## 📌 Project Highlights

- End-to-end classification workflow  
- Clean, modular notebook structure  
- Reproducible results and clear model selection process  
