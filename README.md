# **Analytics Ascend:User Interaction Data Analysis Case Study-competition 2024**
---

## **Overview**

This repository contains the solution for the **User Interaction Data Analysis** case study, submitted as part of the **Analytics Ascend 2024 Competition**. The objective of this project is to analyze a dataset related to user interactions with a platform and derive actionable insights to improve user engagement, retention, and revenue generation. 

---

## **Dataset**

The dataset includes detailed information about users' interactions with the platform. Below is the comprehensive data dictionary for reference:

### **Data Dictionary**
- **C_ID**: Unique Customer ID
- **REG_Date**: User Registration Date
- **FTD_Date**: First Time Deposit (FTD) Date
- **Last_Login_Through**: Platform of Latest Login
- **Age**: Age of the user
- **Gender**: Gender of the user
- **Phone_Verified**: Whether the user's phone is verified
- **Email_Verified**: Whether the user's email is verified
- **KYC**: User's KYC Status
- **FTD_Device**: Device used for First Time Deposit
- **FTD_Amount**: Amount of First Time Deposit
- **REG_Refer_Type**: Referral Type of the Registration
- **REG_Device**: User Registration Device
- **REG_Widget**: User Registration Widget
- **Login_Device**: Device used for User Login
- **App_Type**: App Type used by the user
- **App_Version**: App Version used by the user
- **Total_Deposit**: Total Deposit by the user
- **Total_Wager**: Total Wagered by the user
- **Total_Winning**: Total amount won by the user
- **Total_Withdrawal**: Total Withdrawn by the user
- **Total_Bonus**: Total Bonus earned by the user
- **Last_Deposit_Amount**: Last Deposit made by the user
- **Last_Wager_Amount**: Last Wager made by the user
- **Last_Winning_Amount**: Last Win by the user
- **Last_Withdrawal_Amount**: Last Withdrawal by the user
- **Last_Bonus_Amount**: Last Bonus earned by the user
- **Last_Activity_Date**: Date of Last Activity
- **Last_Deposit_Date**: Date of Last Deposit
- **Last_Wager_Date**: Date of Last Wager
- **Free_Game_Cnt_Till**: Count of Free Games played
- **Deposit_INITIATED**: Number of Deposits initiated by the user
- **Deposit_DONE**: Number of Deposits successfully completed
- **Deposit_FAILED**: Number of Failed Deposits
- **Wager_101_POOL, Wager_201_POOL, etc.**: Cash Game Played Amount across different game types
- **Game_Count_101_POOL, Game_Count_201_POOL, etc.**: Cash Game Count across different game types
- **Days_Count_101_POOL, Days_Count_201_POOL, etc.**: Cash Game Days Count across different game types
- **Total_Game_Count**: Total number of games played
- **Total_Days_Count**: Total number of days the user has participated in games

---

## **Project Objectives**

1. **Data Analysis**: Understand user behavior and identify key trends.
2. **Predictive Modeling**: Develop models to predict churn and estimate user lifetime value.
3. **Insights & Recommendations**: Propose strategies to enhance engagement, retention, and revenue.

---

## **Files in the Repository**

1. **`notebook.ipynb`**  
   The Jupyter Notebook containing the complete analysis, including:
   - Data preprocessing
   - Exploratory Data Analysis (EDA)
   - Feature engineering
   - Predictive modeling and evaluation

2. **`processed_data.csv`**  
   Cleaned and preprocessed dataset used for the analysis.

3. **`presentation.pptx`**  
   Final 5-slide presentation summarizing findings, insights, and recommendations.

4. **`visualizations/`**  
   Folder containing plots and charts used in the analysis.

5. **`models/`**  
   Serialized model files for churn prediction and lifetime value estimation.

6. **`README.md`**  
   This file, providing an overview of the project.

---

## **Approach**

### **1. Data Exploration**
- Examined user demographics, activity levels, and financial transactions.
- Visualized trends and correlations.

### **2. Feature Engineering**
- Created meaningful features such as:
  - Deposit-to-Wager Ratio
  - Days Since Last Activity
  - Average Wager per Game

### **3. Predictive Modeling**
- **Churn Prediction**: Binary classification model to identify users likely to churn.
- **Lifetime Value Prediction**: Regression model estimating a user's potential contribution.

### **4. Insights & Recommendations**
Key recommendations include:
- Implementing bonus programs for user retention.
- Personalized engagement campaigns.
- Enhancing user experiences across platforms.

---

## **Insights Summary**

1. **Demographic Trends**  
   Younger users exhibit higher engagement but churn more quickly.

2. **Financial Behavior**  
   Users with higher initial deposits are more likely to remain active.

3. **Retention Factors**  
   Email and phone verification strongly correlate with user retention.

---

## **Getting Started**

### **Requirements**
- Python 3.12.4 or later
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

### **Run the Notebook**
1. Clone this repository:  
   ```
   git clone <repository-url>
   ```
2. Navigate to the directory:  
   ```
   cd user-interaction-analysis
   ```
3. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:  
   ```
   jupyter notebook notebook.ipynb
   ```

---

## **Submission Details**

This project was submitted as part of the **Analytics Ascend 2024 Competition**.  
- **Submission Deadline**: 3rd Dec 2024, 11:59 PM IST  
- **Submission Link**: [Analytics Ascend Submission Form](https://forms.gle/WtcBQmM9XxgmgxkT6)

---

## **Acknowledgments**

Special thanks to the **Analytics Ascend 2024 Team** for organizing this competition and providing a well-structured dataset and problem statement. 

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

--- 
