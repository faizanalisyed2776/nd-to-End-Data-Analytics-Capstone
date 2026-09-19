# End-to-End Data Analytics Capstone

## About
This project serves as a comprehensive **capstone data analysis workflow**. It integrates every crucial stage of the data science lifecycle into a single, cohesive Python script. It ingests raw data, mitigates outliers and missing values, visualizes trends, mathematically validates hypotheses, trains a predictive classification model, and automatically compiles an executive-ready Microsoft Word report.

## Complete Analytics Pipeline
1. **Data Cleaning:** Imputes missing values (Median) and eliminates statistical noise (IQR method).
2. **Data Visualization:** Utilizes `matplotlib` and `seaborn` to render feature scatter plots and correlation heatmaps.
3. **Statistical Analysis:** Deploys `scipy.stats` to run independent T-Tests validating the financial impact of business interventions.
4. **Machine Learning:** Implements `scikit-learn` to scale features and train a **Random Forest Classifier** to predict high-value customers.
5. **Automated Documentation:** Translates all code outputs, test statistics, and plot images into a beautifully formatted `.docx` file using `python-docx`.

## Prerequisites
Ensure Python is installed along with the data science stack:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels python-docx
