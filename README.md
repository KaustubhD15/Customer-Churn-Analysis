# 📞💡 Customer Churn Analysis for a Telecom Company  

![Customer Churn Analysis_Cover Photo_1]([https://github.com/user-attachments/assets/d3317168-12e6-46ef-adb3-fdbce75f9f92](https://github.com/KaustubhD15/Customer-Churn-Analysis/blob/main/Customer%20churn%20analysis%20image.webp))


## 🌟 **Project Overview**  
The **Customer Churn Analysis Dashboard** utilizes advanced machine learning and data analysis techniques to:  
📉 Predict churn likelihood.  
📊 Identify key factors contributing to churn.  
🔑 Provide actionable insights to improve customer retention strategies.  

This project is developed using **R** in **RStudio**, focusing on visualizing telecom customer data and uncovering patterns that lead to churn.

<br>

## 🎯 **Objectives**  
- 🧠 **Predict** customers likely to leave the service.  
- 🕵️ **Analyze** usage patterns, billing, and customer interactions.  
- 💡 **Recommend** strategies to reduce churn and improve satisfaction.  

<br>

## 📂 **Data Overview**  
📋 The dataset contains **3,334 rows** and **11 columns** from a telecom company:  

| **Column**           | **Description**                                   |
|-----------------------|---------------------------------------------------|
| `Churn`              | 1 if customer left, 0 otherwise.                  |
| `AccountWeeks`       | Weeks the customer has been with the service.     |
| `ContractRenewal`    | Whether the customer renewed their contract (1/0).|
| `DataPlan`           | Indicates if the customer has a data plan (1/0).  |
| `DataUsage`          | Amount of data used (GB).                         |
| `CustServCalls`      | Number of service calls made by the customer.     |
| `DayMins`            | Total minutes of calls during the day.            |
| `MonthlyCharge`      | Customer’s monthly bill.                          |
| `OverageFee`         | Fee charged for exceeding usage limits.           |
| `RoamMins`           | Minutes spent on roaming calls.                   |

<br>

## 🔍 **Analysis Steps**  
1. 🧹 **Data Preprocessing**:  
   - Handle missing values.  
   - Normalize variables for modeling.  

2. 📊 **Exploratory Data Analysis (EDA)**:  
   - Visualize churn rates and key trends.  
   - Analyze patterns such as service call frequency and monthly charges.  

3. 🤖 **Model Building**:  
   - Logistic Regression.  
   - Decision Trees.  
   - Neural Networks.  

4. ⭐ **Feature Importance**:  
   - Key churn predictors include:  
     - 📞 **Customer Service Calls**: 4+ calls significantly increase churn likelihood.  
     - 💳 **Overage Fees**: High fees linked to dissatisfaction.  
     - 📶 **Roaming Minutes**: More roaming usage correlates with churn.  

<br>

## 📈 **Key Insights**  

### **1. Churn Analysis**  
- 🚨 **Churn Rate**:  
  - Overall churn rate is **14.19%**.  
  - **483 out of 3,334 customers** discontinued the service.  
- 📞 **Service Calls**:  
  - Customers making **4+ service calls** are significantly more likely to churn.  
  - **100% churn** for customers with 9+ service calls.  



### **2. Billing Insights**  
- 💳 **High Churn Segments**:  
  - Customers with monthly charges **$75+** churn more frequently.  
  - **Overage Fees** are a major churn driver.  



### **3. Usage Patterns**  
- 📶 **Roaming Minutes**:  
  - Churned customers had higher roaming minutes.  
- ⏳ **Call Durations**:  
  - Longer average call durations correlated with churn.  

<br>

## 🛠️ **Tools & Technologies**  
| **Tool**   | **Purpose**                           |
|------------|---------------------------------------|
| 🎯 **R**   | Data analysis and machine learning.   |
| 💻 **RStudio** | Development environment for R.     |

<br>

## 🌟 **Recommendations**  

### 1. **Enhance Customer Service**  
- 🚀 Focus on customers making **4+ service calls**.  
- 👩‍💻 Provide additional training to resolve issues effectively.  



### 2. **Billing Transparency**  
- 💡 Minimize overage fees with clear billing policies.  
- 🎁 Offer personalized, affordable plans to high-usage customers.  



### 3. **Proactive Retention Strategies**  
- 🔍 Use predictive models to identify at-risk customers.  
- 🎉 Provide loyalty rewards for long-term customers, such as discounts or added benefits.  



### 4. **Personalized Communication**  
- 📢 Engage with high-usage customers to recommend suitable plans.  
- 📈 Create dashboards to monitor churn indicators in real time.  

<br>

## 📸 **Project Visualizations**  

### 📈 **Logistic Regression Insights**  
![image](https://github.com/user-attachments/assets/bb2cbbdb-ed71-4b68-bf4f-12d42f339334)
![image](https://github.com/user-attachments/assets/a46e1141-1482-4cc3-8c38-7989d001e4f8)
![image](https://github.com/user-attachments/assets/e5615ba6-1ebb-45b6-9e67-188965ec19fd)
---

<br>

### 🌲 **Decision Tree Visualization**  
![image](https://github.com/user-attachments/assets/f0b55af8-f6dd-40b0-b076-2d9be28d9904)
---

<br>

### 🧠 **Neural Network Analysis**  
![image](https://github.com/user-attachments/assets/71928b46-8d02-443e-9eb5-de2aa3b181c1)

---

<br>

