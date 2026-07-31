# House Price Prediction with Linear Regression

## Objective

The objective of this project is to build a Linear Regression model that predicts house prices based on different housing features. The project includes data cleaning, exploratory data analysis, feature engineering, model training, and performance evaluation.

---

## Dataset

- **Dataset:** Ames Housing Dataset
- **Source:** Kaggle

---

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook (Anaconda)

---

## Project Workflow

- Imported required libraries
- Loaded the dataset
- Performed initial data inspection
- Checked missing values
- Removed duplicate records
- Handled missing values
- Selected features and target variable
- Applied One-Hot Encoding for categorical features
- Performed Exploratory Data Analysis (EDA)
- Visualized house price distribution
- Created correlation heatmap
- Split the dataset into training and testing sets (80/20)
- Trained a Linear Regression model
- Predicted house prices
- Evaluated the model using MSE, RMSE, and R² Score
- Created Actual vs Predicted Price plot
- Created Residual plot
- Analyzed feature coefficients
- Added conclusion

---

## Visualizations

The following charts were created and saved during this project:

- price_distribution.png
- correlation_heatmap.png
- actual_vs_predicted.png
- residual_plot.png

---

## Results

The Linear Regression model was trained successfully and evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score. The visualizations and evaluation metrics helped measure the model's prediction performance.

---

## Conclusion

This project demonstrates the complete workflow of a machine learning regression model. The model predicts house prices based on housing features and provides insights into the factors that influence property prices.

---

## Repository Structure

```text
DataAnalytics-L3-HousePricePrediction
│
├── HousePricePrediction.ipynb
├── AmesHousing.csv
├── README.md
├── price_distribution.png
├── correlation_heatmap.png
├── actual_vs_predicted.png
└── residual_plot.png
```
