<h1 align="center">
💳Credit Score Classification (Multi-Class): <br> 📈 Optimizing Financial Decision-Making
</h1>

<h3 align="center"> Deep Learning ANN Model </h3>


## Project Overview
<p align="center">
  <img src="https://github.com/Duygu-Jones/DL_Projects/blob/main/01_Credit_Score_Classification_ANN_Model/credit_score_png2x.png"
</p>
  
This project focuses on building a robust **Artificial Neural Network (ANN)** model to predict customer credit scores based on various attributes, including demographic, financial, and behavioural data.   
The objective is to classify customers into three categories: **Good**, **Standard**, and **Poor** credit scores, assisting financial institutions in making informed lending decisions.

## Importance of Credit Score in Finance
A **credit score** reflects a customer's creditworthiness, indicating how likely they are to repay debts on time.    
Financial institutions use credit scores to assess risk, set interest rates, and decide loan terms.    
Customers with **Good** credit scores are seen as low-risk and typically receive better financial terms, while those with **Poor** credit scores are considered high risk, potentially facing higher interest rates or loan rejections.   
Categorizing customers based on their credit scores helps lenders make faster, data-driven decisions.


## Why ANN Model for Credit Score Prediction?
**Artificial Neural Networks** are ideal for this task due to their ability to identify patterns and relationships in complex data. Credit scoring involves multiple interconnected financial factors, and an ANN can capture these interactions to deliver accurate credit score predictions. 


## Business Application
- **Loan Approvals**: By predicting a customer’s credit score, the ANN model helps financial institutions assess the risk of lending to an individual.
- **Interest Rates**: Customers with higher credit scores receive more favourable loan terms, while those with lower scores are considered higher risk.
- **Risk Management**: Accurate credit score predictions enable banks to reduce financial risks and make better lending decisions, ultimately leading to better customer segmentation and optimized loan offerings.    

## Conclusion

This project demonstrates the vital importance of **credit scores** in financial decision-making and risk assessment. By employing an **ANN model**, we've developed a system that accurately classifies customers based on their financial behaviour. This supports critical financial operations, such as loan approvals and setting interest rates, by utilizing advanced deep-learning techniques.

The ANN model's adept handling of imbalanced data is particularly crucial for predicting credit scores. It effectively distinguishes between different creditworthiness levels, which is essential in the financial sector. The model's high recall for potential defaulters minimizes the risks of lending to high-risk individuals, thus reducing financial losses and enhancing the reliability of credit decisions. Its strong generalization capabilities ensure that assessments are both accurate and reliable, aiding financial institutions in making informed, responsible lending decisions and boosting overall financial stability. These achievements highlight the project's impact on improving predictive accuracy and operational efficiency in financial contexts.

 ## 🔍 Key Steps in the Project

- **Exploratory Data Analysis (EDA)**: Conducted a thorough analysis, addressing missing and unusual values while retaining outliers to preserve the data's characteristics. This involved cleaning techniques and imputation where necessary.
- **Data Cleaning**: Removed non-predictive columns such as **ID** and **Name**, focusing on relevant data to boost the model's predictive accuracy.
- **Preprocessing and Data Preparation**:
  - **Encoding Categorical Features**: Converted important categorical data into numerical formats to ensure model compatibility, enhancing the dataset's readiness for predictive modelling.
  - **Data Scaling**: Normalized significant numerical features like **Annual Income** and **Outstanding Debt** to improve model training efficiency and performance.
- **Handling Imbalanced Classes**: Utilized both SMOTE and class weighting techniques to address the class imbalance, with SMOTE proving to be more effective in enhancing model training and validation outcomes.
- **Model Development and Optimization**:
  - Developed an Artificial Neural Network (ANN) that captures complex, non-linear relationships between key features such as **Outstanding Debt**, **Loan Amount**, and **Payment Behavior**, crucial for predicting **Credit Score**.
  - Iteratively optimized the ANN architecture across eight configurations to refine its performance and ensure robustness, ultimately selecting the ANN-7 model with SMOTE for its superior efficacy.
- **Business Application and Impact**: The developed model plays a critical role in aiding financial institutions to make informed lending decisions, set appropriate interest rates, and segment customers for targeted offers based on accurately predicted credit scores.
- **Model Validation**: Tested the final model on a separate test dataset to confirm its effectiveness and reliability in real-world scenarios.

---

## About the Dataset

The dataset consists of customer data, including demographic information, financial history, and payment behaviour, which are important factors in determining credit scores. This data will be processed, cleaned, and engineered to extract the most important features for training the ANN model.    
The target feature is the **Credit_Score**, which classifies customers into three categories based on their financial history:    
1. **Good**: Low-risk customers with strong financial management.
2. **Standard**: Average-risk customers with moderate financial reliability.
3. **Poor**: High-risk customers who may struggle with debt repayments.

- **Dataset:** Credit Score Classification Dataset
- **Content:** Customer demographic, financial, and credit history details.
- **Number of Rows:** 100.000
- **Number of Columns:** 28

| **No** | **INPUTS**                  | **Description**                                                                                  |
|-------|-----------------------------|--------------------------------------------------------------------------------------------------|
| 1     | **ID**                       | Unique identifier for each record.                                                               |
| 2     | **Customer_ID**              | Unique identifier for each customer.                                                             |
| 3     | **Month**                    | Month of the transaction or record.                                                              |
| 4     | **Name**                     | Customer’s name.                                                                                 |
| 5     | **Age**                      | The customer’s age.                                                                              |
| 6     | **SSN**                      | Customer’s social security number.                                                               |
| 7     | **Occupation**               | The customer’s occupation.                                                                       |
| 8     | **Annual_Income**            | The customer’s annual income.                                                                    |
| 9     | **Monthly_Inhand_Salary**    | The customer’s monthly in-hand salary.                                                           |
| 10    | **Num_Bank_Accounts**        | Number of bank accounts owned by the customer.                                                   |
| 11    | **Num_Credit_Card**          | Number of credit cards owned by the customer.                                                    |
| 12    | **Interest_Rate**            | The interest rate applied to loans or credit.                                                    |
| 13    | **Num_of_Loan**              | Number of loans taken by the customer.                                                           |
| 14    | **Type_of_Loan**             | Type of loan taken by the customer.                                                              |
| 15    | **Delay_from_due_date**      | The delay in payment from the due date.                                                          |
| 16    | **Num_of_Delayed_Payment**   | Number of delayed payments made by the customer.                                                 |
| 17    | **Changed_Credit_Limit**     | Changes made to the customer’s credit limit.                                                     |
| 18    | **Num_Credit_Inquiries**     | Number of credit inquiries made.                                                                 |
| 19    | **Credit_Mix**               | The mix of credit types the customer uses (e.g., loans, credit cards).                           |
| 20    | **Outstanding_Debt**         | Total outstanding debt the customer has.                                                         |
| 21    | **Credit_Utilization_Ratio** | The ratio of credit used to the total credit limit.                                               |
| 22    | **Credit_History_Age**       | The length of the customer’s credit history.                                                     |
| 23    | **Payment_of_Min_Amount**    | Whether the customer pays the minimum amount required each month.                                |
| 24    | **Total_EMI_per_month**      | The total EMI (Equated Monthly Installment) the customer pays each month.                        |
| 25    | **Amount_invested_monthly**  | The amount invested by the customer each month.                                                  |
| 26    | **Payment_Behaviour**        | The payment behavior of the customer.                                                            |
| 27    | **Monthly_Balance**          | The customer’s remaining balance at the end of each month.                                        |
| 28    | **Credit_Score**             | The customer’s credit score (target variable: "Good," "Poor," "Standard").                        |

    
- > *This dataset is ideal for developing credit risk assessment models, allowing for a detailed analysis of the factors that impact an individual’s credit score.*    
- > *Original dataset is available on Kaggle:* [Credit score classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification/data?select=train.csv)
    
---    

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Credit Score Classification EDA + ANN Model💳💹](https://www.kaggle.com/code/duygujones/credit-score-classification-eda-ann-model)
 - The dataset is available to download on the Kaggle: [Credit score classification]([https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/datasets/parisrohan/credit-score-classification))

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Duygu Jones, a Data Scientist, passionate about data analysis, and machine learning.

♻️ You can find more about me and my work through the following links:

- **Linkedin**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)

🌐Feel free to connect with me!

<br>

🎯 Enhance your machine learning skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---

##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
