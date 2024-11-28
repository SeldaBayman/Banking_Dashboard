# Banking Data Analysis Project | Power BI

![Banking Analysis](https://example.com/your-image.png)

## 🚀 Overview
Welcome to the **Banking Data Analysis Project**! In this project, we dive deep into a banking dataset using **Power BI** to generate meaningful insights, including customer behaviors, financial patterns, and key performance indicators (KPIs) for the banking industry.

Through this analysis, we explore key client demographics, such as gender and loyalty classification, as well as significant financial metrics like bank deposits, credit card balances, and risk weightings. The ultimate goal is to provide actionable insights for better business decision-making and targeted customer strategies.

## 📊 Dataset Overview
The dataset contains critical information about clients and their banking relationships, covering various aspects of income, property ownership, risk levels, and deposits. Below is a quick look at the data columns:

### Client Information

- **Client ID**: Unique identifier for each client.
- **Estimated Income**: The estimated annual income of the client.
- **Gender**: Gender of the client.
- **Loyalty Classification**: Categorizes clients based on their loyalty to the bank (e.g., loyal, new, dormant).
- **Properties Owned**: The number of properties owned by the client.

### Banking Information

- **Bank Deposits**: The total deposits made by the client into their bank account.
- **Credit Card Balance**: The current balance on the client's credit card.
- **Risk Weighting**: The calculated risk profile for each client based on their financial behavior and history.
- **Banking Relationship**: Type of banking relationship (e.g., personal, corporate, etc.).
The data spans multiple years, providing a comprehensive look at how clients’ financial behaviors evolve over time.

## 💡 Key Insights & Reports

### 1. **Average Properties Owned by Gender**
   This report provides a breakdown of average properties owned by clients segmented by gender, allowing for deeper insights into property ownership patterns across genders.

**2. Total Bank Deposits by Gender**
This visualization helps us understand the total deposits made by clients, segmented by gender. It provides insights into how different genders contribute to the overall bank deposit pool.

**3. Client Loyalty Classification & Total Income**
This report highlights the total income generated by clients, segmented by their loyalty classification. This is critical in identifying the income distribution across loyal and non-loyal customers.

**4. Correlation Between Estimated Income and Credit Card Balance**
A fascinating insight into whether higher income correlates with higher credit card balances, helping the bank assess financial behavior and risk levels.

**5. Risk Weighting vs. Properties Owned Correlation**
This report explores whether there’s any significant relationship between the number of properties owned by clients and their risk weighting. This analysis can help the bank in its risk management strategies.

**⚙️ DAX Measures and Functions Used**
In this project, we leveraged several powerful DAX functions to manipulate the data and generate meaningful insights:

*CALCULATE: Used to apply additional filters and modify the context of the calculation.
SUM: To calculate total sums for various metrics like deposits and properties.
AVERAGE: To find the average values, such as average income or average number of properties owned.
FILTER & RELATEDTABLE: To apply custom filters to related tables for accurate segmentations.
SUMMARIZE/SUMMARIZECOLUMNS: For creating summary tables for client loyalty classifications and income segmentation.
SQRT and DIVIDE: Used to compute correlations between different financial variables.

**🎯 Key Takeaways**
The project highlights critical customer metrics, such as income distribution, credit card balances, and deposits.
By correlating income and risk metrics with property ownership, the analysis helps to understand customer profiles and potential risk factors.
It allows banks to focus on key loyalty segments and identify high-value customers with higher income and more properties owned.

**🚀 How to Use This Project**
Clone or download the repository.
Open the Banking_Analysis.pbix file in Power BI Desktop.
Explore the various dashboards and reports created in this project.
Customize and modify the analysis or add new data as needed.
Feel free to tweak the existing visualizations and DAX calculations to fit your own data needs or project requirements.

**📃 License**
This project is licensed under the MIT License - see the LICENSE file for more details.
