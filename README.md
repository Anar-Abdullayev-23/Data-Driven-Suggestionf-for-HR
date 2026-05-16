<<<<<<< HEAD
# Data-Driven HR: Predicting and Preventing Employee Turnover
Machine Learning for HR Employee Churn Prediction and Analysis
=======
## OVERVIEW
The goal of this project is to use data to understand exactly why employees quit and how to keep them. By analyzing historical employee data, we built a system that **predicts whether an employee will leave with 96.2% accuracy**. More importantly, this project provides actionable HR strategies to improve retention and employee satisfaction.

## BUSINESS UNDERSTANDING
* **Business Problem:** High turnover costs the company money and loses top talent. The objective is to stop guessing why people leave and use data to uncover the root causes (like burnout or unfair evaluations) so we can fix our HR policies.
* **Stakeholders:** HR Directors, Talent Acquisition Teams, and Executive Leadership.

## DATA UNDERSTANDING
* **Source:** We analyzed a dataset of corporate employee records (`HR_comma_sep.csv`).
* **Size:** We looked at over 12,000 clean employee records (after removing duplicates). It included real-world factors like satisfaction levels, performance reviews, project counts, and monthly hours worked.

## MODELING AND EVALUATION
Instead of relying on gut feelings, we tested several advanced data models to find patterns in human behavior. The winning model (Random Forest) was incredibly reliable, **identifying at-risk employees with 96.2% accuracy**. 

The data revealed that the **top 4 hidden drivers of employee turnover** are:
1. Their last performance evaluation score
2. The number of projects they are assigned
3. Their tenure (years spent at the company)
4. Being overworked

## RESULTS AND RECOMMENDATIONS
To immediately improve employee retention, the data suggests HR and management implement the following strategies:

* **Optimize Workloads:** **100% of employees assigned to 7 projects left the company.** The data shows the "sweet spot" for maximum retention is **3 to 4 projects**. We must cap concurrent project assignments.
* **Redefine "High Performance":** Currently, **high evaluation scores are almost exclusively given to employees working 200+ hours a month.** We need to stop rewarding pure burnout and start rewarding efficiency and impact.
* **Address the Overwork Crisis:** Employees logging 250-300 hours a month have a drastically higher quit rate. **If overtime is necessary, it must be matched with fair compensation, promotions, or mandatory recovery time.**
* **Target the 4-Year Mark:** Employees hitting their 4-year anniversary show a high risk of dissatisfaction. **HR should implement targeted "stay interviews" and career-pathing discussions for employees approaching their 4th year.**
