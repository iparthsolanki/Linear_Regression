# Marketing Campaign Performance Analysis

A comprehensive machine learning and data analysis project focused on analyzing marketing campaign performance and predicting campaign revenue using Python and Linear Regression.

---

## Overview

This project analyzes marketing campaign data to understand how different campaign factors influence revenue generation and overall campaign performance.

The project includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature engineering
- Revenue categorization
- Linear Regression model building
- Revenue prediction
- Model evaluation

The goal of this project is to identify the key drivers of campaign success and predict future campaign revenue using machine learning techniques.

---

## Business Problem

Marketing campaigns generate large amounts of performance data, but businesses often struggle to identify:

- Which campaign channels perform best
- Which factors impact revenue generation
- How marketing spend affects ROI
- Which campaigns generate better conversions
- How to predict campaign revenue effectively

This project helps businesses make data-driven marketing decisions by analyzing campaign performance metrics and building predictive models.

---

## Objective

The main objectives of this project are:

- Analyze marketing campaign performance data
- Identify factors affecting campaign revenue
- Perform Exploratory Data Analysis (EDA)
- Build a machine learning model for revenue prediction
- Evaluate model performance using regression metrics
- Generate business insights for marketing optimization

---

## Dataset Information

The dataset contains detailed information related to marketing campaign performance.

### Columns Included in the Dataset

- Impressions
- Clicks
- Leads
- Conversions
- Cost_USD
- ROI
- Revenue_USD
- Channel
- Campaign Details

These features are analyzed to understand campaign effectiveness and revenue generation patterns.

---

## Technologies and Libraries Used

### Programming Language
- Python

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Project File

- `Campaighn_Performance.ipynb` → Main project notebook

---

## Project Workflow

### 1. Data Collection
- Imported marketing campaign dataset
- Loaded data into Pandas DataFrame

### 2. Data Cleaning and Preprocessing
- Removed unnecessary columns
- Checked missing values
- Converted categorical data using encoding
- Prepared dataset for machine learning

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis using histograms
- Correlation analysis using heatmaps
- Channel-wise campaign analysis
- Revenue category analysis

### 4. Feature Engineering
- Created Revenue Categories:
  - Low
  - Medium
  - High
- Applied Label Encoding
- Converted categorical features into numerical format

### 5. Correlation Analysis
Pearson Correlation was used to identify relationships between:
- Impressions
- Clicks
- Leads
- Conversions
- ROI
- Revenue

### 6. Machine Learning Model
Implemented:
- Linear Regression Model

### 7. Model Evaluation
Evaluated model performance using:
- R² Score
- Adjusted R² Score
- Actual vs Predicted Revenue Comparison

---

## Analysis Performed

### Campaign Performance Analysis
- Revenue analysis
- ROI analysis
- Conversion analysis
- Lead generation analysis

### Channel Performance Analysis
- Email campaign performance
- Social media campaign analysis
- Influencer campaign analysis
- Search campaign analysis

### Revenue Prediction Analysis
- Predicted future campaign revenue
- Compared actual vs predicted revenue
- Evaluated model accuracy

---

## Visualizations Used

The project includes multiple visualizations such as:

- Histograms
- Heatmaps
- Countplots
- Scatter Plots
- Correlation Matrix
- Actual vs Predicted Revenue Plot

These visualizations help identify trends, patterns, and relationships in campaign performance data.

---

## Machine Learning Details

### Model Used
- Linear Regression

### Target Variable
- Revenue_USD

### Features Used
- Impressions
- Clicks
- Leads
- Conversions
- Cost_USD
- ROI
- Campaign Channels

### Data Preparation Techniques
- Train-Test Split
- StandardScaler
- Label Encoding
- One-Hot Encoding

---

## Key Insights

- Campaign channels significantly impact revenue generation
- Higher conversions and leads positively influence revenue
- ROI plays a major role in campaign success
- Revenue prediction can help optimize future marketing strategies
- Data-driven marketing analysis improves decision-making

---

## Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Statistical Analysis
- Machine Learning
- Linear Regression
- Data Visualization
- Model Evaluation
- Business Insight Generation

---

## How to Run the Project

1. Download the `.ipynb` file
2. Open it using Jupyter Notebook or Google Colab
3. Install required Python libraries
4. Run all notebook cells sequentially
5. Explore the analysis and prediction results

---

## Business Use Cases

- Marketing campaign optimization
- Revenue forecasting
- Customer acquisition analysis
- ROI performance tracking
- Digital marketing analytics
- Business intelligence reporting

---

## Future Improvements

- Implement advanced regression models
- Add feature selection techniques
- Build interactive dashboards
- Apply hyperparameter tuning
- Perform real-time campaign analysis

---

## Contribution

Contributions are welcome. Feel free to fork this repository and improve the project.

---

## License

This project is created for educational and portfolio purposes.

---

## Author

Parth Solanki
