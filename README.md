# Day-7  
# ⚙️ Support Vector Machines (SVM) for Binary Classification

## 📌 Objective
This project demonstrates the use of **Support Vector Machines (SVMs)** for both linear and non-linear classification on a binary classification dataset. The goal is to understand how SVMs work and how tuning hyperparameters affects model performance.

---

## 🛠️ Tools & Libraries Used
- Python 3  
- NumPy – for numerical operations  
- Scikit-learn – for dataset preparation, model training, hyperparameter tuning, and evaluation  
- Matplotlib – for visualizing decision boundaries  

---

## 📂 Dataset
- Dataset used: `titanic_cleaned.csv` (or any binary classification dataset)  
- Cleaned and preprocessed data for binary classification.  
- Target column: `Survived` (0 = did not survive, 1 = survived) or binary class label.

---

## 📈 Project Workflow

1. **Data Loading and Preparation**  
   - Loaded dataset using `pandas`.  
   - Handled missing values and encoded categorical features.  
   - Selected features relevant for classification.  
   - Split data into training and testing sets.  
   - Scaled features using `StandardScaler` for better SVM performance.

2. **Training SVM Models**  
   - Trained an SVM classifier with a **linear kernel**.  
   - Trained an SVM classifier with an **RBF (Gaussian) kernel** to capture non-linear relationships.

3. **Visualization of Decision Boundaries**  
   - Visualized decision boundaries of both linear and RBF kernel SVMs on 2D feature subsets for interpretability.

4. **Hyperparameter Tuning**  
   - Tuned hyperparameters such as `C` (regularization) and `gamma` (kernel coefficient for RBF) using grid search or manual experimentation.

5. **Model Evaluation**  
   - Evaluated models using accuracy score, confusion matrix, and classification reports.  
   - Used cross-validation to assess generalization performance and robustness.

---

## 📊 Output & Results
- Comparison of linear vs RBF kernel SVM performance.  
- Decision boundary plots illustrating classifier separation on 2D features.  
- Model metrics including accuracy, precision, recall, and F1-score.  
- Insights on how hyperparameter tuning affects classification results.

---

## 📌 Conclusion
This project highlights the power of SVMs in handling both linear and complex non-linear classification problems, with a focus on feature scaling, kernel choice, hyperparameter tuning, and robust model evaluation.

---

*M. Sathvika*  
*Date: 05-06-2025*
