# 📘 Influence of Feature Scaling on Convergence in Linear Models  
**Course:** CS725 — Foundations of Machine Learning  
**Team Members:** Harsh Khurana, Pansuriya Tarang Bharatbhai, Aatmaj Mhatre  

---

## 📁 Project Overview
This project investigates how different **feature-scaling techniques** influence the **convergence, performance, and stability** of various **linear machine learning models**.  
The analysis covers both **classification and regression datasets**, focusing on metrics such as MAE, MSE, R², Accuracy, F1-score, and Convergence Time.

The main experimentation workflow, model implementation, scaler comparison, and plots are contained in the notebook:

👉 **`FML_project.ipynb`**

---

## 📂 Repository Structure
.
├── FML_project.ipynb         
├── Rice_Cammeo_Osmancik.csv     
├── README.md                

---

## 📥 Dataset Requirement

The dataset **`Rice_Cammeo_Osmancik.csv`** is **not available through an online link**, so:

> ⚠️ **Before running the notebook, please upload this CSV file in the runtime (e.g., Google Colab or Jupyter environment).**

You can do this by using the upload dialogue in Colab/Jupyter or placing the file in the same directory as the notebook.

---

## ▶️ How to Run the Notebook

1. Open `FML_project.ipynb` in **Google Colab** or your preferred Jupyter environment.  
2. **Upload `Rice_Cammeo_Osmancik.csv`** when prompted in the data-loading cell.  
3. Run all cells **sequentially** from top to bottom.  
4. The notebook will:
   - Load datasets  
   - Apply multiple feature-scaling methods  
   - Train linear models  
   - Measure convergence time  
   - Compute evaluation metrics  
   - Generate comparison plots  
5. All results (tables, plots, comparisons) will be produced inside the notebook.

---

## 🧪 Models Used
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Linear SVR  
- Logistic Regression (SGD)  
- Linear SVM (SGD)  
- Perceptron  

---

## 📊 Scaling Techniques Evaluated
- Standardization (Z-score)  
- Min–Max Scaling  
- MaxAbs Scaling  
- Robust Scaling  
- Pareto Scaling  
- VAST Scaling  
- No Scaling (Baseline)  

---

## 🎯 Project Objective
To determine **how different feature-scaling techniques affect**:
- Convergence speed  
- Training stability  
- Model performance across datasets  
- Sensitivity of linear models to feature distributions  

---

## ✔️ Reproducibility
We use:
- **Google Colab environment**
- **Python 3**
- **scikit-learn** for all models and scalers  
- A fixed `random_state=42` in all models to ensure reproducibility  

---

## 🙌 Acknowledgments
We thank **Prof. Abir De** for guidance and IIT Bombay for enabling this coursework.

