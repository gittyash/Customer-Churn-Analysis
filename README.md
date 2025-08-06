# Customer Churn Analysis & Power BI Dashboard

This repository contains an end-to-end analysis of telecom customer churn. The project cleans and analyzes a raw dataset, extracts key insights using Python, and presents the findings in an interactive Power BI dashboard.

---

## 📊 Project Overview

The primary goal of this project is to identify the key drivers of customer churn. By understanding why customers leave, a business can develop targeted strategies to improve retention. The analysis covers customer demographics, contract details, service adoption, and payment methods.

### Key Files in this Repository:
* `Customer Churn.csv`: The raw, unprocessed dataset used for the analysis.
* `Customer_Churn_Analysis.ipynb`: A Jupyter Notebook containing all the Python code for data cleaning, exploratory data analysis (EDA), and visualization.
* `Churn_Dashboard.pbix`: The final Power BI dashboard file for interactive data exploration.

---

## 💡 Key Insights from the Analysis

The analysis uncovered several significant factors that influence customer churn:

* **Contract Type is Critical:** Customers on a **month-to-month contract** have a significantly higher churn rate (over 42%) compared to those on one-year or two-year contracts.
* **New Customers are at High Risk:** Churn is most prevalent among customers with a short **tenure** (1-2 months). Loyalty increases dramatically the longer a customer stays.
* **Payment Method Matters:** Customers using **Electronic Check** as their payment method are far more likely to churn (45%) than those using automatic payment methods.
* **Senior Citizens Churn More:** Senior citizens show a higher propensity to churn (41.7%) compared to younger customers.
* **Lack of Key Services:** Customers without services like `OnlineSecurity` and `TechSupport` are more likely to leave.

---

##  dashboards Preview

Below is a screenshot of the main dashboard, which provides a high-level overview of the key metrics and churn drivers.

>

![Dashboard Preview](https://i.imgur.com/your-dashboard-screenshot-url.png)

---

## 🛠️ Tools & Technologies Used

* **Data Analysis:** Python (Pandas, Matplotlib, Seaborn)
* **Notebook:** Jupyter Notebook
* **Dashboarding:** Microsoft Power BI

---

## 🚀 How to Use

1.  **Clone the repository:**
    ```
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Explore the Analysis:** Open the `Customer_Churn_Analysis.ipynb` file in a Jupyter environment to see the step-by-step data analysis.
3.  **View the Dashboard:** Open the `Churn_Dashboard.pbix` file in Power BI Desktop to interact with the dashboard.
