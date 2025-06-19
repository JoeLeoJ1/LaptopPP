# 💻 Laptop Price Prediction

This project focuses on predicting the price of laptops based on various features using machine learning models. The notebook walks through the data preprocessing steps, feature engineering, model training, and evaluation to build a robust predictive system.

## 📁 Project Structure

- `LaptopPP.ipynb`: Main Jupyter Notebook containing all steps from EDA to model evaluation.
- `laptops.csv` *(not included)*: Dataset file assumed to be used for training and testing.
- `README.md`: Project overview and instructions.

## 📊 Features Used

The dataset includes features such as:
- Brand
- Processor
- RAM size
- Storage (SSD/HDD)
- Operating System
- Display size
- GPU
- Weight
- Touchscreen availability

Categorical features are encoded, and numerical ones are scaled for optimal model performance.

## 🧠 Models Applied

Several models are trained and evaluated to find the best predictor:
- Linear Regression
- Lasso Regression
- Ridge Regression
- Random Forest Regressor

The best model is selected based on performance metrics such as:
- R² Score
- Mean Absolute Error (MAE)

## 🛠️ How to Run

1. Clone the repository or download the notebook.
2. Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook LaptopPP.ipynb

