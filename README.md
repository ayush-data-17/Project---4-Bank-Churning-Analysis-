# 🏦 Project-4-Bank-Churning-Analysis-
An in depth  **data anlaytics and visualization project** built by using **Python (EDA)** and **Power BI** , amied at analyzing the trend of churning or exited from the bank by various factors .

---
## 📘 Project Overview 
This project is about analysing the churning effect of customers with respect to various factors. It helps to answer the following question :
- How churn most male or females ?
- Does tenure play important role in churning ?
- Does country play important role in churning ?
- How does memebership affect the churning rate ?
- How does age group affect the churning rate ?
- how does credit score impact the churning ?

---
## 📁 Dataset Details 

 - Source : https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset
 - Rows : Over 10,000
 - Columns Name : Columns ID , Surname , Hascrcard , Isactivememeber , Exited , Geography , Gender , Balance , Estimated Salalry , Age , Row ID , Numofproducts , Tenure

---
## 🧹 Data Cleaning and Data Visualizations
All the preprocessing , Data Cleaning and Visuals of the data were done by  python using **pandas , numpy , matplolib and seaborn**

### Steps Performed :
- Handelled the missing values by filling them using mean/mode in the numeric columns.
- Cleaned all the null values , duplicates and irrelevant columns like **Row ID and Surname**
- Converted the data types of the columns.
- Done some feature engineering/Created New columns like **Balance Category , Salary category and Credit Score Category etc.**
- Replaced the values in **Exited** by **Left And Stayed** , and **Hascrcard** by **Yes or No .**
- Done with some visualization to find relationship between exited column and other columns to get some insights from it . 
- Generated summary satistics using **describe()** and **Correlation analysis**.

---

## 📊 Dashboards and Features 
**1. Exicutive Summary**

<img width="1098" height="721" alt="Screenshot 2025-11-20 123822" src="https://github.com/user-attachments/assets/2a6f56e1-656e-4de9-aeb7-9acffa5b860b" />


**Features:**

**KPI'S:**
- Total Customers: 10k
- Total Exited : 2037
- Average Credit Score : 650
- Churn Rate %: 20%


**Charts And Visualizatiion:**
- Filled Map: France has the highest number of customer distribution than the other countries . 
- Column Chart: Customers having fair credit score in more number than the others . 
- Bar Chart: Adult group are more in customer distribution in age group than seniors and young one .
- Doughnut Chart: Males are the more than the females(54% males ) . 

---

**2. Customer Segmentation**

<img width="1105" height="716" alt="Screenshot 2025-11-20 123829" src="https://github.com/user-attachments/assets/a45cf205-1aff-43df-9fb3-786bb107c1c4" />



**Features:**

**KPI'S:**
- Total Customers: 10k
- Average Age: 38.92
- Average Credit Score: 650
- Average Balance: 76.49k


**Charts And Visualization:**
- Line Chart: Customers having tenure between 4 to 6 years are more numbers . 
- Column Chart: Customers seems to be in more numbers having high salary(5.5k) . 
- Bar Chart: Customrs having medium balance account are in more numbers . 
- Column Chart: Customer having only 1 products from the bank  are in more numbers than the others . 

---

**3. Churning Analysis**

<img width="1106" height="721" alt="Screenshot 2025-11-20 123835" src="https://github.com/user-attachments/assets/2630a8d1-5bcb-4ae1-beae-8e5522f668ed" />


**Features:**

**KPI'S:**
- Total Exited: 2037
- Average Tenure Exited: 4.96
- Churn Rate%: 20%
- Average Credit Score Exited: 645.35


**Charts And Visualization:**
- Column Chart: Adult age category have churned most . 
- Doughnut Chart: Females Have churned most fromthe bank than the males (Females - 55.92% , Males - 45.08%) . 
- Pie Chart: Non Active members have churned most than the active member of bank( Non Active - 66% , Active - 36%) . 
- Column Chart: Germany is the country that churned most form the bank than the other country . 

---

# 📊 Key Insights from Bank Customer Churn Analysis

**⭐ 1. Female Customers Churn More**

**Female customers** show a higher churn rate compared to males, indicating a need for gender-focused retention strategies.

**⭐ 2. Adults Contribute the Highest Churn**

**The Adult age group** has the largest customer base and the highest number of customers who left the bank.

**⭐ 3. Germany Has the Highest Churn**

Among all regions, **Germany** shows the highest exit rate, clearly standing out as a churn hotspot.

# 🧍‍♂️ Customer Behaviour Insights
**⭐ 4. Inactive Customers Are Most Likely to Churn**

**Non-active members** show a churn rate of ~13%, significantly higher than active users.

**⭐ 5. Fewer Products = More Churn**

Customers who hold only **one product** have a higher churn tendency than multi-product customers.

**⭐ 6. Tenure Has Minimal Impact on Churn**

Length of customer relationship does not strongly influence churn. Customers churn regardless of how long they've been with the bank.

# 💰 Financial Behaviour Insights
**⭐ 7. Medium Balance Customers Churn More**

Customers with a **medium account balance** (not too low, not too high) show the highest churn probability.

**⭐ 8. Poor & Fair Credit Score Drives High Churn**

Customers with **Poor or Fair** credit scores churn significantly more than those with Good, Very Good, or Excellent scores.

**⭐ 9. Majority of Customers Stay**

Overall, 80% of customers remain with the bank, while 20% churn — highlighting a significant retention opportunity.
---

## 💼 Recommendation

Based on the analysis here are some recommendation for theber company that can help them in the better decision making:

1. **Increase driver incentives** during the peak hours to aviod cancellations
2. offer **discounts or loyalty programs** for online payments to increase digital adoptaion.
3. Use **demand forecasting** to position more vehicle in high demand locations.
4. Focus on **traning and support** for drivers in the low rated zones .

---

## 🧰 Tools Used 

- **Python:** pandas, numpy, matplotlib, seaborn
- **Power BI:** For dashboard making , creating DAX problems and building report
- **EDA:** For doing bivaraite and univariate analysis on the dataset and creating some basic visualizations .

---

## 🔗 Connect With Me 

- **Author:** Ayush Lohat
- **Linkdin:** www.linkedin.com/in/ayush-lohat-463187381
- **GitHub:** https://github.com/ayush-data-17
- **Data Source:** **https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?select=ncr_ride_bookings.csv

---

✨ *Thank you for exploring this project! Your feedback and suggestion are always welcome .*

  



 
 

