# Logistic Regression from Scratch on Glass Dataset

This project implements **Logistic Regression from scratch** (without using any machine learning libraries) on the **UCI Glass Identification Dataset**.

The objective is to understand the internal working of Logistic Regression, including the sigmoid function, loss computation, and gradient descent optimization.

---

## Dataset

- **Dataset Name:** Glass Identification Dataset  
- **Source:** UCI Machine Learning Repository  
- **Total Samples:** 214  
- **Features:** 9 chemical properties of glass  
- **Target:** Glass Type  

For simplicity, the multi-class problem is converted into a **binary classification task**:
- Class `1` → Glass type 1  
- Class `0` → All other glass types  

---

## Project Workflow

1. Load and inspect the dataset  
2. Assign column names manually (dataset has no headers)  
3. Convert labels to binary classes  
4. Normalize features using NumPy  
5. Split data into:
   - Training set  
   - Validation set  
   - Test set  
6. Implement Logistic Regression **from scratch**:
   - Sigmoid activation
   - Binary Cross-Entropy loss
   - Gradient Descent optimization
7. Evaluate model performance using accuracy

---

## Implementation Details

- **Language:** Python  
- **Libraries Used:**  
  - `NumPy` – numerical computations  
  - `Pandas` – data loading and visualization only  
 No machine learning libraries such as `scikit-learn` are used for model training.

---

## Files
- `logistic_regression_glass.ipynb` – Jupyter Notebook containing the full implementation
- `glass.data` – Dataset file 

---

## Key Learning Outcomes

- Understanding Logistic Regression mathematically  
- Implementing sigmoid activation and loss functions manually  
- Training a model using gradient descent  
- Working with real-world datasets without ML libraries  

---
