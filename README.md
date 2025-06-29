# Placement-Prediction-Using-Machine-Learning

# 🧠 Placement Prediction Using Machine Learning

This project predicts whether a student will be placed or not based on their academic records, test scores, and work experience using multiple machine learning models.

---

## 📂 Dataset

The dataset includes the following features:

- **Academic Scores**: SSC %, HSC %, Degree %, MBA %
- **Boards/Streams**: SSC Board, HSC Board, HSC Stream, Degree Type
- **Work Experience**: Yes/No
- **Employability Test Score**
- **Specialisation**
- **Target Variable**: `status` (Placed / Not Placed)

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Dropped unnecessary columns (`sl_no`, `salary`)
   - Applied Label Encoding to categorical columns
   - Scaled numerical features using `StandardScaler`
   - Ensured target column `status` is encoded as integers (0/1)

2. **Train-Test Split**
   - Used 80% for training and 20% for testing

3. **Model Training & Evaluation**
   - Models used:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
     - Naive Bayes
   - Evaluation metric: **Accuracy Score**

---

## 📊 Sample Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 0.86     |
| SVM                | 0.83     |
| Decision Tree      | 0.81     |
| Random Forest      | 0.88     |
| Naive Bayes        | 0.79     |

> Note: Results may vary slightly depending on the data split and random state.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualization)

---

## 🔮 Future Enhancements

- Hyperparameter tuning using GridSearchCV
- Try advanced models like XGBoost or LightGBM
- Add Cross-validation for better evaluation
- Create a Streamlit or Flask web app for deployment

---

---

## ✍️ Author

**Speranza Deejoe**  
---

## 📜 License

This project is intended for educational and academic purposes only.



