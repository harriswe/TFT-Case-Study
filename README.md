# Conceptual TFT Case Study: Demand Forecasting

##### **Disclaimer**: *Fictional scenario based on public ML practices, not tied to any real project or proprietary data.*

### **Problem**: A fictional e-commerce platform needs weekly demand forecasts to optimize inventory.

### **Approach**:  
- Built a theoretical Temporal Fusion Transformer (TFT) using `pytorch_forecasting`.  
- Used mock data with static features (e.g., product categories) and time-varying inputs (e.g., public holiday flags from Kaggle).  
- Optimized hyperparameters with Optuna for efficient model tuning.  
- Tracked experiments using MLFlow to log metrics and model versions.  
- Validated with rolling cross-validation for robust forecasting.

### **Challenges**: Handled irregular data with TFT’s imputation and attention mechanisms.

### **Outcome**: Hypothetical forecasts improved inventory planning.

### **Visual**:  
![TFT Loss Curve](/chart.png)  
*Caption*: Mock TFT validation loss, created for this fictional case study.

### **Key Skills**:  
- **Machine Learning**: Temporal Fusion Transformer (TFT) modeling, time series forecasting, feature engineering (static and time-varying features).  
- **Tools & Libraries**: Python (`pytorch_forecasting`, `pandas`, MLFlow, Optuna).  
- **Techniques**: Hyperparameter optimization (Optuna), experiment tracking (MLFlow), rolling cross-validation, attention-based modeling.
