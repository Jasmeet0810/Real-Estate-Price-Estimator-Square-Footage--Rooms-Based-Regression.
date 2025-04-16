Real Estate Price Estimator
A simple Linear Regression model to predict real estate prices based on square footage and number of rooms. Built with pandas, scikit-learn, and seaborn, and fully runnable in Google Colab.

Project Structure
real-estate-price-estimator/
├── real_estate_data.csv       # Sample dataset
├── price_estimator.ipynb      # Jupyter notebook (Colab-ready)
├── README.md                  # Project documentation

Features
Clean dataset with square footage, room count, and prices
Trains a Linear Regression model using scikit-learn
Evaluates model with R², MSE, RMSE, and MAE
Predicts price for new data inputs
Includes visualizations (scatter, pairplot, heatmap)
100% accuracy on clean dataset; noise can be added for realism

Requirements
Python 3.x
pandas, numpy, matplotlib, seaborn, scikit-learn
Can be run directly in Google Colab (no setup needed)

How to Use
Clone the repo or download the notebook
Open price_estimator.ipynb in Google Colab
Run each cell step-by-step
Edit inputs to predict prices for new houses

Example Output
R² Score: 1.00
MSE: 0.00
RMSE: 0.00
MAE: 0.00
Predicted Price: $430,000.00

To-Do / Extensions
Add real-world data (e.g., from Zillow, Kaggle)
Introduce location, year built, or other features
Deploy as a web app using Streamlit or Flask
