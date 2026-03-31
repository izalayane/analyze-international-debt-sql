🌍 Analyze International Debt Statistics
📌 Project Overview

In this project, I analyzed international debt data provided by the World Bank to better understand how developing countries manage external debt.

The dataset contains information about different types of debt indicators, including total debt and repayment values, measured in current US dollars.

The goal of this analysis was not only to extract data, but to identify patterns, generate insights, and interpret economic implications behind the numbers.

- The dataset does not include a time variable, which prevents trend analysis
- It likely represents a snapshot of data from a specific period

🗂️ Dataset Description

The dataset includes the following fields:

country_name → Name of the country
country_code → Country code
indicator_name → Description of the debt indicator
indicator_code → Code for each indicator
debt → Value of the debt (in USD)
🎯 Key Business Questions

During the analysis, I focused on answering:

How many countries are present in the dataset?
Which country has the highest total debt?
Which country has the lowest principal repayment?
🛠️ SQL Techniques Used
COUNT(DISTINCT ...) → to identify unique countries
GROUP BY → to aggregate debt values per country
SUM() → to calculate total debt
ORDER BY → to rank results
LIMIT → to isolate top/bottom cases
Filtering with WHERE using indicator codes
📊 Key Findings & Insights
🌐 Number of Countries

The dataset contains multiple developing countries, allowing comparative analysis across different economic contexts.

💰 Country with Highest Debt
China was identified as the country with the highest total debt.

📌 Insight:
This likely reflects the country's large economic scale and significant investment in infrastructure and development projects, which often require external financing.

📉 Country with Lowest Principal Repayment
Timor-Leste showed the lowest repayment value for principal debt.

📌 Insight:
This may indicate either:

A lower overall debt burden
Limited repayment capacity
Or fewer active debt instruments compared to larger economies


🧠 Analytical Approach

Instead of only extracting results, I focused on:

Interpreting what each metric represents in a real-world context
Identifying possible economic explanations behind the data
Raising hypotheses that could be validated with additional datasets

📎 Project Structure
SQL queries answering each business question
Aggregations and filtering based on economic indicators
🔗 Connect with Me

Feel free to connect or reach out:

👉 [www.linkedin.com/in/iza-soares]

💡 Final Thoughts

This project demonstrates how even simple SQL queries can generate meaningful insights when combined with analytical thinking and business context.

The focus is not just on what the data shows, but on what it means.