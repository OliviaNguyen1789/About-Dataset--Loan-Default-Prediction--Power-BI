



# Project Title: Loan Dataset - Loan-Default Prediction | Power-BI



Author: [Olivia Nguyen]  
Date: March 2025  
Tools Used: Power BI 

---

## 📑 Table of Contents  
I. [📌 Background & Overview](#-background--overview)  
II. [📂 Dataset Description](#-dataset-description)  
III.[🧠 Design Thinking Process](#-design-thinking-process)  
IV.[📊 Power BI Visualization](#-power-bi-visualization)  
V. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)


## 📌 Background & Overview

### 📖 What is this project about?
The objective of this project is to analyze a loan default dataset using Power BI to identify key factors contributing to defaults. This involves assessing borrower risk profiles based on attributes such as income, age, home ownership, and employment duration, as well as evaluating loan characteristics like loan grade, amount, interest rate, and duration. By examining historical default patterns and current loan status, the findings will help optimize lending strategies, improve risk management, and enhance overall loan portfolio performance.
  
### 👤 Who is this project for?   

The insights gained will empower the following stakeholders to make informed strategic decisions and enhance financial operations:
- Financial Institutions: Assess borrowers’ ability to repay their debt on time, preventing the issuance of non-performing loans and optimizing lending policies.
- Borrowers: Predict loan default risk to guide personal finance decisions, helping to prevent long-term negative financial consequences.
- Other Stakeholders: Evaluate individuals' financial capacity before providing services, ensuring more informed decision-making.

### ❓ Business Questions:
- What are the key factors that contribute to loan defaults?
- Which borrower segments have the highest default risk, and how can they be managed effectively?

## 📂 Dataset Description

### 🌐 Data Source
- The Loan Default dataset originates from Kaggle and can be accessed at:  https://kaggle.com/datasets/prakashraushan/loan-dataset/data
- Size: 32,600 rows, 13 columns
- Format: .csv

### 🔀 Table schema
<details>
<summary>Table: Churn Prediction </summary>  

| Number | Variable name       | Definition                                                | Data Type |
| ------ | ------------------- | --------------------------------------------------------- | --------- |
| 1      | customer_id         | Unique identifier for each customer                       | Text      |
| 2      | customer_age        | Age of the customer                                       | Text      |
| 3      | customer_income     | Annual income of the customer                             | Number    |
| 4      | home_ownership      | Annual income of the customer                             | Text      |
| 5      | employment_duration | Duration of employment in months                          | Number    |
| 6      | loan_intent         | Purpose of the loan                                       | Text      |
| 7      | loan_grade          | Grade assigned to the loan                                | Text      |
| 8      | loan_amnt           | Loan amount requested                                     | Number    |
| 9      | loan_int_rate       | Interest rate of the loan                                 | Number    |
| 10     | term_years          | Loan term in years                                        | Number    |
| 11     | historical_default  |  Indicates if the customer has a history of default (Y/N) | Text      |
| 12     | cred_hist_length    |  Length of the customer's credit history in years         | Number    |
| 13     | Current_loan_status | Current status of the loan (DEFAULT, NO DEFAULT)          | Text      |

</details>


## 🧠 Design Thinking Process

### 1️⃣ Empathize

<img width="1008" alt="Screen Shot 2025-03-05 at 11 08 14 AM" src="https://github.com/user-attachments/assets/3b9bdd1a-2650-4643-9c88-a2950659d6f0" />

### 2️⃣ Define point of view

<img width="1392" alt="Screen Shot 2025-03-05 at 1 26 08 PM" src="https://github.com/user-attachments/assets/94a855f0-af37-42c0-96a0-428b17bee0ba" />

### 3️⃣ Ideate

<img width="844" alt="Screen Shot 2025-03-05 at 1 59 59 PM" src="https://github.com/user-attachments/assets/1aef1909-7b90-4bae-9624-910c6b31aa4f" />

### 4️⃣ Prototype and review  
Next, I iterated through multiple cycles of prototyping and review to refine the final result, which will be presented in the following section as a dashboard.


## 📊 Power BI Visualization
### Dashboard 1 Preview

![bi1](https://github.com/user-attachments/assets/f209033e-69c1-4145-8f3f-0188d9c9e331)


**🚀 Scrap rate:**

- Scrap Rate is Low (0.24%), indicating an efficient production process. However, even small percentages can be costly, especially if high-value products are affected.

- Scrap rate is especially high in the third quarter each year, suggesting seasonal factors affecting production quality.

- The  most common reasons for scrap products is related to paint process.

**🚀 Manufacturing Time:**

- High Late Ratio (31.4%): Over 1 in 3 work orders are late, suggesting systematic inefficiencies rather than isolated incidents.
  
- Late Orders increase with work order volume. When production demand rises, the system struggles to scale, leading to more late orders.
Potential Causes: Poor production planning, material shortages, Overloaded production capacity—not enough machines or labor to meet demand, defects—scrap or quality issues.

- Subassembly and final assembly are the two production stages that are most likely to be delayed.
  

### Dashboard 2 Preview

![bi2](https://github.com/user-attachments/assets/194588a1-e7c8-475e-b61d-81a4fdd07a30)



- 🚀 Scrap Rate shows a positive correlation with order quantity, consistently peaking in the third quarter each year, with a notable surge in 2013. This increase may stem from overloaded production capacity—insufficient machines or labor to meet rising demand, leading to inefficiencies and higher scrap rates.
  The 2013 peak could be attributed to shifts in production methods, material changes, or workforce adjustments, potentially disrupting efficiency and quality control.

- 🚀 High-Volume Products (BB Ball Bearing, Seat Stays, Chain Stays, Blades) have low defect rates  --> Identify process control techniques used in these lines that could help high-defect products.
  
- 🚀 Most common reasons of high scrap rate:  Seat assembly not as ordered, Drill size too large, Paint process fail name, Trim length too long, Thermoform temperature issue

- 🚀 Highest scrap cost by reason: Color incorrect, Trim length too long, Thermoform temperature issue, Drill size too large. These defects result in high financial losses, making them a priority for cost reduction.

- 🚀 Remarkably, while seat assembly errors contribute the most to scrap rate, their financial impact (cost) is minimal. In contrast, color incorrect defects — despite their low scrap rate — incur the highest costs. Given this, minimizing scrap caused by color incorect should be the top priority for cost reduction.


### Dashboard 3 Preview

![bi3](https://github.com/user-attachments/assets/0aafcb59-cfaf-4cdd-9aaf-cbad7abc84c6)



- 🚀 The late ratio has shown an upward trend from 2011 to 2014, rising from 29.47% in 2011 to 36.65% in 2014. In general, late orders rise with work order volume, suggesting that the system struggles to scale due to factors such as material shortages and overloaded production capacity.

- 🚀 Scheduled Time remained constant from 2011 to 2014, while Actual Production Time showed a slight decline. Notably, Actual Production Time consistently exceeds Scheduled Time, with the gap widening in March, May, August, and September. This pattern suggests inefficiencies in planning, unexpected disruptions, or capacity constraints affecting production efficiency.

- 🚀 Nearly 30% of late-delivered orders are caused by delays in production start dates.

- 🚀 The Mountain Product Group having the largest average number of days late in delivery indicates a systemic issue that needs targeted attention. 
  Possible Causes: More Complex Manufacturing Process, Higher Demand Volume → If mountain bikes are a best-seller, backlog issues might arise.


### Dashboard 4 Preview

![bi4](https://github.com/user-attachments/assets/c87f1b1c-2865-4346-8aa9-9d13e105279c)



- 🚀 Late delivery ratios have increased over time across production stages, meaning the issue is systematic rather than temporary.
  Possible Causes: Inefficient Resource Allocation, Delays in earlier production stages causing a snowball effect.

- 🚀 Currently, capacity is almost evenly distributed across production stages, creating imbalances where stages requiring more production time face shortages, while others have excess capacity. As a result, Subassembly, Final Subassembly, and Frame Forming & Welding experience the highest late delivery ratios due to insufficient capacity in these critical stages.
  
- 🚀 In the production stages, Frame Forming and Frame Welding incur significantly higher costs, with production expenses being twice as high as those in the remaining stages.


## 🔎 Final Conclusion & Recommendations 

| Issue                                                                                                                                                              | Recommended Action            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------|
| Seasonal Scrap Rate Increase in Q3 – Likely due to capacity strain from high demand.                                                                               | Expand capacity during peak months (July–September) through additional shifts or outsourcing. Enhance forecasting and scheduling to better manage seasonal demand.                           |
| High Cost of Color-Incorrect Defects – Despite a low scrap rate, these defects incur significant costs.                                                            | Improve color accuracy with enhanced quality control measures and calibration tools to minimize defect-related expenses.                                                                     |
| Rising Trend of Late-Delivery Orders – Indicates capacity constraints, inefficient scheduling, and start-time delays.                                              | Optimize scheduling and enhance production start-time accuracy to mitigate delays. Strengthen raw material forecasting and supplier reliability to prevent disruptions.                      |
| Production Time Exceeding Scheduled Time – Particularly in March, May, August, and September, pointing to workload strain and poor scheduling during peak periods. | Refine production planning and adjust schedules to accommodate high-demand months more effectively.                                                                                          |
| Mountain Product Group Faces the Largest Delays – Attributed to product complexity, high demand, and supply chain challenges.                                      | Streamline production for mountain products, potentially by establishing dedicated production lines. Address supply chain bottlenecks and prioritize material allocation for mountain bikes. |
| Subassembly and Final Assembly Experience the Most Delays – Likely due to capacity overloads.                                                                      | Balance workloads across production stages and implement lean manufacturing principles. Expand capacity in subassembly and final assembly where necessary.                                   |
