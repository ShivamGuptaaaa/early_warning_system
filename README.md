# 🎓 Early Warning System for Identifying At-Risk Students Using Predictive Analytics

## 📌 Overview
This project is designed to help educators and administrators identify at-risk students early on by leveraging **predictive analytics**. By analyzing student data, such as **attendance records, grades, behavioral incidents, and socioeconomic factors**, the system generates timely alerts, enabling proactive interventions to improve student outcomes.

## 🛠️ Key Features
- **Data Integration and Cleaning:** Combine and preprocess multiple data sources, ensuring consistency and quality.
- **Feature Engineering:** Extract meaningful features like **attendance rate, grade trends, and behavioral patterns** to enhance model accuracy.
- **Predictive Modeling:** Train and deploy multiple machine learning models to predict students at risk of **academic failure, absenteeism, or behavioral issues**.
- **Risk-Based Alerts:** Automatically generate alerts for at-risk students, including **detailed insights and suggested interventions**.
- **Notification System:** Send alerts to educators via email or a dedicated dashboard, ensuring **timely and actionable** notifications.

## 📊 Exploratory Data Analysis (EDA)
The EDA revealed key insights into student performance and behavior:

1. **Total Score Comparison (2021 vs. 2023):** Identifies trends in academic performance over time.
2. **Average Total Score by Risk Category:** Highlights performance variation among different risk levels.
3. **Impact of Behavioral Risk on Average Scores:** Analyzes how behavioral issues correlate with academic performance.
4. **Risk Category Distribution:** Visualizes the distribution of students across risk categories.
5. **Grades Impact on Total Average Score:** Examines how grades affect overall performance.
6. **Pairplot for Risk Factors:** Provides a multi-dimensional view of how various risk factors interact.

## 📈 Machine Learning Models
Three machine learning models were developed and fine-tuned for optimal performance:

- **Logistic Regression**
- **Random Forest Classifier**
- **Gradient Boosting Machine**

The best-performing model was selected based on **evaluation metrics** like **accuracy, precision, recall, and F1-score**.

## 🚨 Alert and Notification System
The system generates alerts for students flagged as "at-risk" by the model. Alerts include key details such as:

- **Attendance Rate**
- **Average Grades**
- **Behavioral Risk Levels**
- **Suggested Interventions**

Educators receive these alerts via **email notifications**, allowing them to take timely and informed actions.

## 🤖 Technical Stack
**Programming Language:** Python
**Libraries:** Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn, Flask
**Notification System:** SMTP for email alerts

