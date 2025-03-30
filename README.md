# Linear Regression Health Costs Calculator

## Overview
This project predicts healthcare costs using **Linear Regression** based on patient details such as age, BMI, smoking status, and region. The model is trained on a dataset of medical expenses and evaluated based on **Mean Absolute Error (MAE)** to ensure accurate predictions.

## Dataset
The dataset contains the following features:
- **age**: Age of the patient
- **sex**: Gender of the patient
- **bmi**: Body Mass Index
- **children**: Number of dependents
- **smoker**: Smoking status (Yes/No)
- **region**: Residential region
- **expenses**: Medical expenses (Target variable)

## Project Workflow
1. **Data Preprocessing**
   - Handle categorical variables using **One-Hot Encoding**.
   - Normalize numerical features using **StandardScaler**.
2. **Model Training**
   - Split the dataset into **80% training** and **20% testing**.
   - Train a **Linear Regression** model.
3. **Model Evaluation**
   - Evaluate performance using **Mean Absolute Error (MAE)**.
   - Ensure MAE is **below 3500** for successful prediction.
4. **Visualization**
   - Generate a **scatter plot** comparing actual vs. predicted medical expenses.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/linear-regression-health-costs.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```sh
   python health_costs.py
   ```

## Results
- The trained model predicts healthcare costs with an **MAE under $3500**.
- Visualization shows a strong correlation between **actual and predicted values**.

## Future Improvements
- Implement **Regularization (Ridge/Lasso)** to enhance model performance.
- Use **Polynomial Regression** or **Neural Networks** for better predictions.
- Explore additional datasets to generalize predictions further.

## License
This project is open-source under the **MIT License**.

---
**Author:** Ranjeeth Kumar Patra

