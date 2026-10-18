# HR-Insights | Employee Attrition Analytics

## 📌 Project Overview

HR-Insights is a data analytics and machine learning project focused on understanding employee attrition and identifying workforce trends. The project analyzes employee data to explore factors associated with employee turnover and generate meaningful insights that can support data-driven HR decisions.

The project uses Python for data analysis, Snowflake for cloud data storage and querying, machine learning for attrition prediction, and Streamlit for an interactive dashboard.

## 🎯 Objectives

- Analyze employee attrition patterns.
- Explore department-wise attrition and overtime trends.
- Understand relationships between employee characteristics and attrition.
- Build a machine learning model to predict employee attrition.
- Present analytical insights through an interactive application.

## 🔄 Project Workflow

**AWS → Snowflake → Data Analysis → Machine Learning → Streamlit Dashboard**

1. **AWS:** Source and store HR data.
2. **Snowflake:** Load and query HR data in a cloud data platform.
3. **Data Analysis:** Clean and explore the data using Python and Pandas.
4. **Exploratory Data Analysis:** Examine attrition patterns and workforce trends.
5. **Machine Learning:** Train a model to predict employee attrition.
6. **Streamlit Dashboard:** Display insights and model predictions through a web application.

*Note: Include the AWS-to-Snowflake workflow only if it is implemented in your project.*

## ✨ Key Features

- Employee attrition analysis
- Department-wise attrition insights
- Overtime-related attrition analysis
- Salary and attrition trend analysis
- Machine learning-based attrition prediction
- Interactive Streamlit application
- Snowflake connectivity for data access

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly (if used)
- **Cloud Data Platform:** Snowflake
- **Cloud Storage:** AWS (if implemented)
- **Machine Learning:** Scikit-learn (if used)
- **Web Application:** Streamlit
- **Version Control:** Git and GitHub

## 📂 Project Structure

```text
HR-Insights/
├── app.py
├── main.py
├── requirements.txt
├── .gitignore
├── models/
│   └── attrition_model.pkl
└── src/
    ├── connect_snowflake.py
    ├── eda.py
    └── train_model.py
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/krutikaghodkhande/HR-Insights.git
cd HR-Insights
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment on Windows

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure credentials

Configure the required Snowflake connection details and any necessary cloud credentials using environment variables or Streamlit secrets. Do not upload passwords, access keys, or tokens to GitHub.

### 6. Run the application

```bash
streamlit run app.py
```

## 📊 Expected Outcomes

- Better understanding of employee attrition patterns
- Identification of workforce trends
- Data-driven insights for employee retention analysis
- Interactive access to attrition analytics and predictions

## 🔮 Future Enhancements

- Automate data ingestion from AWS to Snowflake
- Schedule regular data updates
- Improve model evaluation and prediction performance
- Deploy the dashboard using Streamlit Community Cloud
- Add further HR analytics metrics

## 👩‍💻 Author

**Krutika Ghodkhande**

GitHub: [krutikaghodkhande27](https://github.com/krutikaghodkhande)
