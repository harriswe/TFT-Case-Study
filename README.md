# Conceptual TFT Case Study: Demand Forecasting

> **Disclaimer**  
> This is a fictional scenario based on public machine learning practices.  
> No real project or proprietary data is used.

---

## Problem
A fictional e-commerce platform needs **weekly demand forecasts** to optimize inventory management and reduce stockouts/overstocking.


## Approach
1. **Modeling**
   - Built a *theoretical* Temporal Fusion Transformer (TFT) using `pytorch_forecasting`.
   - Incorporated:
     - **Static features** — e.g., product categories.
     - **Time-varying inputs** — e.g., public holiday flags from open Kaggle datasets.
2. **Optimization**
   - Used **Optuna** for hyperparameter tuning.
   - Applied **rolling cross-validation** to validate model robustness.
3. **Experiment Management**
   - Logged metrics and model versions in **MLFlow** for reproducibility.


## Challenges
- Managed irregular data via TFT’s **imputation** capabilities.
- Leveraged TFT’s **attention mechanisms** to focus on key temporal drivers.


## Outcome
- **Hypothetical** forecasts indicated improved inventory planning in the fictional scenario.
- Demonstrated how TFT can integrate static and dynamic features for demand prediction.


## Visual
**Caption:** Mock TFT validation loss (generated for this fictional case study).  

![TFT Visual](/chart.png)


## Key Skills

### Machine Learning
- Temporal Fusion Transformer (TFT) modeling  
- Time series forecasting  
- Feature engineering (static & time-varying features)  

### Tools & Libraries
- Python  
- `pytorch_forecasting`  
- `pandas`  
- `MLFlow`  
- `Optuna`  

### Techniques
- Hyperparameter optimization (**Optuna**)  
- Experiment tracking (**MLFlow**)  
- Rolling cross-validation  
- Attention-based modeling
