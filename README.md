# Analysing a 10x20 DataFrame with Machine Learning ✨📊

This project demonstrates the creation of a meaningful **10x20 DataFrame** and the application of a machine learning model to predict diabetes outcomes. It showcases feature engineering, model training, and evaluation using Python and popular ML libraries.

---

## 🔧 Features
1. **DataFrame Generation**:
   - **Columns**:
     - Age, BMI, BloodPressure, Cholesterol, Glucose, Insulin, SkinThickness, FamilyHistory, ExerciseLevel, Diabetes.
   - **Rows**:
     - 20 samples of synthetic health data with randomized values.

2. **Preprocessing**:
   - One-hot encoding for categorical variables (ExerciseLevel).

3. **Machine Learning**:
   - Logistic Regression for binary classification.

4. **Evaluation**:
   - Accuracy Score: 0.67.
   - Detailed Classification Report.

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/gaurav069/Analyzing-a-10x20-DataFame-with-Machine-Learning..git
   cd Analyzing-a-10x20-DataFame-with-Machine-Learning.
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Execute the script:
   ```bash
   python dataframe_mlmodel.py
   ```

---

## 🕊️ Example Output
### Sample DataFrame:
| Age | BMI  | BloodPressure | Cholesterol | Glucose | Insulin | SkinThickness | FamilyHistory | ExerciseLevel | Diabetes |
|-----|------|---------------|-------------|---------|---------|---------------|---------------|---------------|----------|
| 56  | 18.94| 130           | 220         | 83      | 41.14   | 30            | 0             | Medium        | 0        |
| 69  | 39.35| 86            | 193         | 164     | 35.93   | 18            | 1             | High          | 1        |
| ... | ...  | ...           | ...         | ...     | ...     | ...           | ...           | ...           | ...      |

### Model Accuracy:
```
Model Accuracy: 0.67
```

### Classification Report:
```
              precision    recall  f1-score   support
           0       0.80      0.80      0.80         5
           1       0.50      0.50      0.50         1
    accuracy                           0.67         6
   macro avg       0.75      0.75      0.67         6
weighted avg       0.83      0.67      0.67         6
```

---

## 📖 Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `scikit-learn` for machine learning.

---

## 🙏 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
