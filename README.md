# 🩺 Diabetes Prediction using K-Nearest Neighbors (KNN)

A machine learning project that predicts whether a patient has diabetes
using the KNN classification algorithm on the Pima Indians Diabetes Dataset.

---

## 📁 Project Structure

```
├── KNN_Diabetes.ipynb       # Main Jupyter Notebook
├── diabetes_dataset.csv     # Dataset
└── README.md                # Project documentation
```

---

## 📊 Dataset

- **Source:** Pima Indians Diabetes Database
- **Rows:** 768 patients
- **Features:** 8 medical attributes
- **Target:** `Outcome` — 1 (Diabetic) / 0 (Non-diabetic)

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skinfold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes hereditary score |
| Age | Age in years |

---

## ⚙️ Steps Performed

1. **Data Import & Exploration** — shape, dtypes, missing values
2. **Data Preprocessing** — replaced invalid zeros with column medians; applied StandardScaler
3. **Train/Test Split** — 80% train, 20% test (stratified)
4. **KNN Implementation** — tested K = 1 to 25, selected best K
5. **Model Evaluation** — accuracy, confusion matrix, ROC-AUC, classification report

---

## 📈 Results

| Metric | Value |
|---|---|
| Accuracy | ~78% |
| ROC-AUC | ~0.84 |
| Best K | 11–15 |

---

## 🛠️ Libraries Used

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn notebook

# Launch Jupyter
jupyter notebook KNN_Diabetes.ipynb
```

---

## 👤 Author

**Your Name**  
B.Tech — Electronics & Communication Engineering  
Heritage Institute of Technology, Kolkata
