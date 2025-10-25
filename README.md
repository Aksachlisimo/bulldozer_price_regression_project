# 🚜 Bulldozer Price Prediction

### 📘 Overview
A machine learning project predicting auction sale prices of bulldozers using historical sales data.  
The project follows a full ML pipeline — from data preprocessing and feature engineering to model training and evaluation.

## 🧠 Objectives
- Predict bulldozer sale prices accurately.  
- Explore relationships between features and sale price.  
- Train and evaluate regression models.

## ⚙️ Tools & Libraries
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 🚀 Workflow
- Data Loading & Cleaning  
- Exploratory Data Analysis (EDA)  
  - Checked distributions of features  
  - Visualized correlations between variables  
- Feature Engineering & Encoding  
- Model Training  
  - Linear Regression  
  - Random Forest Regressor  
- Model Evaluation  
  - Root Mean Squared Logarithmic Error (RMSLE)  

## 📊 Results
- **Best Model:** RandomForestRegressor  
- **RMSLE Achieved:** ~0.25 (from notebook metrics)  
- **Key Influencing Features:** YearMade, MachineHoursCurrentMeter, ModelID, SaleDay  

## 📈 Visual Insights
- Older machines tend to sell for lower prices.  
- Machine hours and model type significantly impact sale price.  
- Sale timing (month/day) shows minor seasonal trends.

## 🧩 Key Takeaways
- Gained hands-on experience with end-to-end regression ML pipelines.  
- Improved skills in data preprocessing, feature engineering, and model evaluation.  
- Learned to interpret model performance and extract actionable insights for pricing.

## 📁 Notebook
- [View Project Notebook](./end-to-end-bluebook-bulldozer-price-regression.ipynb)

## 🛠️ Setup Instructions
- Clone the repository: `git clone https://github.com/mrdbourke/zero-to-mastery-ml.git`  
- Install dependencies: `pip install -r requirements.txt` *(create if not present: pandas, numpy, matplotlib, seaborn, scikit-learn)*  
- Open the notebook in Jupyter and run all cells.

## 👨‍💻 Author
- Mohamed Mouhimine  
- AI & Machine Learning Engineer
