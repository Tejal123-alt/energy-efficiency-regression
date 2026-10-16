# Energy Efficiency Regression Assignment

## Project Overview
This project compares three regression techniques to predict the heating load of buildings using the Energy Efficiency dataset.

## Dataset
- Dataset: Energy Efficiency
- Samples: 768
- Input features: 8 original features (X1–X8)
- Target variable: Y1 (Heating Load)
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/242/energy+efficiency)

## Models Implemented
1. Simple Linear Regression
2. Polynomial Regression (Degree 2)
3. Multivariate Linear Regression

## Methodology
- Dataset inspection and preprocessing
- Feature selection and categorical encoding
- 80:20 training-testing split
- Model training and prediction
- Evaluation using MSE, RMSE, and R²
- Comparative analysis and visualization

## Results

| Model | MSE | RMSE | R² |
|---|---:|---:|---:|
| Simple Linear Regression | 62.8489 | 7.9277 | 0.3970 |
| Polynomial Regression | 60.9388 | 7.8063 | 0.4154 |
| Multivariate Linear Regression | 8.2500 | 2.8723 | 0.9209 |

## Best Performing Model
Multivariate Linear Regression achieved the best test-set results among the three evaluated models.

## Tools and Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Download the notebook and dataset from this repository.
2. Open the notebook in Google Colab.
3. Upload the Excel dataset when prompted.
4. Run the cells in order to reproduce the analysis.

## Author
Tejal Haridas Gadhe
