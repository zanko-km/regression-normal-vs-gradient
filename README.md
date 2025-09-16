# Normal vs Gradient Linear Regression

This project implements **Linear Regression** using two different approaches:

## 1. Normal Equation
- Closed-form solution:  
        θ = (Xᵀ X)⁻¹ Xᵀ y
- No need for a learning rate or initial guess.  
- Computationally expensive for large datasets (matrix inversion).  
- Minimal sensitivity to data ordering.  

## 2. Gradient Descent
- Iterative optimization algorithm.  
- Requires learning rate and initial parameters.  
- More efficient on large datasets.  
- Results can be affected by initialization and data ordering.  

---

## Results & Comparison

- **Normal Equation**  
  - High computational cost.  
  - Stable, no need for initial values.  
  - Least affected by data ordering.  

- **Gradient Descent**  
  - Faster for large-scale problems.  
  - Sensitive to learning rate and initialization.  
  - Performance may vary with data preprocessing.  

---

## 📌 Conclusion
- **Normal Equation** → Simple, stable, but computationally heavy.  
- **Gradient Descent** → Scalable, but sensitive to hyperparameters and data handling.  
