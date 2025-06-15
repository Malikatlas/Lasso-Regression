# Lasso Regression - Muscle Mass Percentage Prediction

This project addresses a regression problem where the goal is to predict the **muscle mass percentage** of individuals using:
- Daily Protein Intake (grams)
- Exercise Hours per Week
- Hydration Level (liters/day)

### 📌 Problem Statement
Using the given dataset, we:
1. Perform 3 iterations of **Lasso Regression** with:
   - Regularization parameter α = 0.05
   - Learning rate η = 0.0001
2. Report updated weights (w₁, w₂, w₃), bias (b), and Mean Squared Error (MSE) after each iteration
3. Use the final model to predict muscle mass percentage for a new individual with:
   - 105g protein/day
   - 7.5 hours of exercise/week
   - 3.6L hydration/day
4. Discuss the role of regularization and effects of a high α

### 🧪 Dataset

| Protein (g) | Exercise (hrs/wk) | Hydration (L/day) | Muscle Mass (%) |
|-------------|-------------------|-------------------|------------------|
| 80          | 5                 | 3.0               | 45               |
| 100         | 7                 | 3.5               | 50               |
| 90          | 6                 | 3.2               | 48               |
| 110         | 8                 | 4.0               | 55               |
| 95          | 6.5               | 3.8               | 50               |

Iteration 1: w = [0.9488, 0.06512, 0.03494], b = 0.00992, MSE = 2470.80
Iteration 2: w = [0.1553, 0.01042, 0.00577], b = 0.00170, MSE = 1729.42
Iteration 3: w = [0.8189, 0.05593, 0.03021], b = 0.00865, MSE = 1210.93


**Predicted Muscle Mass % for (105g, 7.5hr, 3.6L):** `≈ 86.52`

### 🧠 Concepts

- **Lasso Regression**: A regularized linear regression technique that can shrink coefficients and enforce sparsity.
- **Regularization (α)**: Helps avoid overfitting. High values of α can shrink coefficients to zero, possibly underfitting the model.

### 🗂️ Files
- `Question.pdf` – Original assignment
- `Solution (1).pdf` – Manual calculations
- `Solution (2).pdf` – Python code and final results

---



