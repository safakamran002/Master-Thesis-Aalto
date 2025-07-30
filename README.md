# Master-Thesis-Aalto

# Results – Master's Thesis: Predicting CO₂ Emissions of Private Transport in Helsinki Using Transfer Learning

This folder contains the **results generated from machine learning models** used in the master's thesis titled:

**“Predicting CO₂ Emissions of Private Transport in Helsinki Region Using Transfer Learning”**  
_Aalto University – Department of Geoinformatics_  
Author: Safa Kamran

## Contents

The folder includes key result outputs from the thesis, particularly:

- **Feature Importance Graphs**: Visualizing top predictors (e.g., car distance, trip frequency, built area).
- **Model Performance Tables**: Metrics such as R², MAE, RMSE for Random Forest, HistGradientBoosting, and Linear Regression.
- **Hexagonal Emission Maps (H3 Grids)**: Spatial distribution of predicted emissions in Helsinki based on Espoo-trained models.
- **Comparison Plots**: Visual comparison of model predictions vs actual values across hexagons.

## Models Used

- **Random Forest**
- **HistGradientBoosting**
- **Linear Regression**

All models were trained using **Espoo-origin H3-based OD data** and transferred to the **Helsinki H3 grid**.

## Tools and Libraries

- Python 3.10
- Scikit-learn
- SHAP
- Pandas, NumPy, Matplotlib
- H3-Py (for hexagonal spatial indexing)

## Purpose of Results

These outputs validate the **feasibility of using transfer learning** in urban emission modeling when local training data are sparse. The results provide evidence for:

- Model interpretability
- Generalization capability of Espoo-trained models in Helsinki
- The impact of built environment variables on CO₂ predictions
- Suitability of H3 indexing for fine-resolution spatial prediction


## Contact

For questions, collaboration, or related inquiries:  
**Email**: safakamran02@gmail.com  
**GitHub**: [@SafaKamran](https://github.com/SafaKamran)

