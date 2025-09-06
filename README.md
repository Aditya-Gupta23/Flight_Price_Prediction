# Flight Price Prediction

This project builds machine learning and deep learning models to predict flight ticket prices.  
The dataset was cleaned, preprocessed, and stored in a `.pkl` file for reproducibility.  

## Models Implemented
1. **Neural Network (TensorFlow/Keras)**
   - Architecture: 64 → 32 → 1 dense layers
   - Loss: Mean Squared Error (MSE)
   - Metric: Mean Absolute Error (MAE)
   - Training with early validation for performance tracking.

2. **Decision Tree Regressor (Scikit-learn)**
   - Captures non-linear relationships
   - Simple, interpretable model

3. **Random Forest Regressor (Scikit-learn)**
   - Ensemble of decision trees
   - More robust and generalizes better than a single tree

Here we reached accuracy of 88% using Neural Networks, 91.95% using Decision Trees and 92.85% using Rnadom Forest
