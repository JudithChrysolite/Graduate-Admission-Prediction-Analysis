# Graduate-Admission-Prediction-Analysis
# 🎓 Graduate Admission Prediction Analysis

This project applies **machine learning** to predict a student's *chance of admission* to a graduate program, based on their academic profile. The goal is to assist students in assessing their admission likelihood and help universities evaluate applications more effectively.

---

## 📌 Problem Statement

Given historical admission data, predict the **Chance of Admit** (a continuous value between 0 and 1) for new student profiles using features such as:

- GRE Score
- TOEFL Score
- University Rating
- SOP Strength
- LOR Strength
- CGPA
- Research Experience

---

## 📊 Dataset Overview

Each record in the dataset includes:

| Feature            | Description                                 |
|---------------------|---------------------------------------------|
| **GRE Score**       | GRE exam score (out of 340)                 |
| **TOEFL Score**     | TOEFL exam score (out of 120)               |
| **University Rating**| Rating of the university (1 to 5)          |
| **SOP**             | Strength of Statement of Purpose (1–5)      |
| **LOR**             | Strength of Letter of Recommendation (1–5)  |
| **CGPA**            | Undergraduate GPA (out of 10)               |
| **Research**        | Research experience (0 = No, 1 = Yes)       |
| **Chance of Admit** | Target variable (range: 0.0–1.0)            |

---

## 🚀 Project Workflow

1️⃣ **Data Loading and Cleaning**
   - Handle missing or inconsistent values
   - Scale and normalize features

2️⃣ **Exploratory Data Analysis (EDA)**
   - Visualize distributions
   - Analyze correlations

3️⃣ **Feature Engineering**
   - Select important features
   - Encode categorical variables if necessary

4️⃣ **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - (Optional: Support Vector Regressor, XGBoost)

5️⃣ **Model Evaluation**
   - R² Score
   - Mean Squared Error (MSE)
   - Cross-validation results

6️⃣ **Prediction**
   - Estimate admission probability for new profiles

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Example Results

> *Best Model:* Random Forest Regressor  
> *R² Score:* ~0.85  
> *MSE:* ~0.012  

*(Note: Actual results depend on hyperparameters and random seed)*

---

## 💻 How to Run This Project

1. Clone or download this repository.
2. Install dependencies (recommended: set up a virtual environment):
    ```
    pip install -r requirements.txt
    ```
    *(If requirements.txt is not provided, install libraries manually)*

3. Open Jupyter Notebook:
    ```
    jupyter notebook
    ```

4. Open and run all cells in:
    ```
    ML_Project_new.ipynb
    ```

5. Modify input cells at the end of the notebook to predict new student profiles.

---

