# House Price Prediction (Zameen.com)

A machine learning project that analyzes Pakistani property listings from Zameen.com and predicts house prices using regression models.

## Dataset

`zameen-updated.csv` contains about 168,000 property listings with details such as:

- **Property:** type, purpose (sale/rent), area size, area type and category
- **Rooms:** bedrooms, baths
- **Location:** city, province, locality, latitude, longitude
- **Listing info:** date added, agency, agent
- **Target:** price

## What the notebook does

1. **Data cleaning:** fills missing values, removes invalid prices and coordinates, standardizes text, drops duplicates
2. **Outlier handling:** winsorization on price, area, rooms, and coordinates
3. **Feature engineering:** price per sqft, baths per bedroom, bedrooms per floor, and a listing-age feature
4. **Modeling:** trains and compares three models:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
5. **Evaluation:** MAE, MSE, and R² on a held-out 20% test set

## Files

- `code.ipynb`: main notebook
- `zameen-updated.csv`: dataset
- `House_Price_Analysis_Report.pdf`: written analysis report

## How to run

1. Clone the repository:
   `git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git`
2. Install the libraries:
   `pip install pandas numpy scipy scikit-learn seaborn matplotlib jupyter`
3. Launch the notebook:
   `jupyter notebook code.ipynb`

Keep the CSV in the same folder as the notebook.

## Results

Add your best model and its R² / MAE here after running the notebook.

## Author

Your Name
