# MARKETING-ANALYSIS-PROJECT-SQL-PYTHON-
In this propject, I Analysed marketing campaign performance using SQL and Python to identify high-performing campaigns and key customer characteristics influencing campaign acceptance.



Marketing Campaign Analysis
PROJECT OVERVIEW

This project analyses the effectiveness of multiple marketing campaigns using customer demographic, behavioural, and transactional data. The goal is to understand which campaigns perform best, which customers are most responsive, and what factors influence campaign acceptance, in order to support data-driven marketing decisions and budget optimisation.

The analysis follows a real-world analytics workflow, combining SQL for data preparation and validation with Python (Pandas, Seaborn, Matplotlib) for exploratory data analysis (EDA) and insight generation.

BUSINESS PROBLEM
The business invests in several marketing campaigns but lacks clear visibility into:

Which campaigns are most effective

Whether high-value customers respond differently to marketing efforts

Whether customer income influences campaign acceptance

Without this understanding, marketing spend risks being inefficient or misallocated. The objective of this project is to provide evidence-based insights that help marketing stakeholders decide which campaigns to continue, optimise, or discontinue.

DATA  DESCRIPTION

The dataset contains customer-level information including:

Campaign acceptance indicators (AcceptedCmp1–AcceptedCmp5)

Demographics (Income, Education, Marital Status)

Purchase behaviour (spend across multiple product categories)

Recency and engagement metrics

A derived TotalSpend variable was created by summing spending across all product categories. A Responsive flag was created to indicate whether a customer accepted at least one campaign.

Methodology

The project followed these steps:

Data Cleaning & Preparation (SQL & Python)

Removed missing and inconsistent records

Standardised formats and column values

Created cleaned analysis-ready tables

Feature Engineering (Python)

Created TotalSpend to represent customer value

Created a Responsive flag (accepted ≥1 campaign)

Exploratory Data Analysis (Python)

Compared campaign acceptance counts and rates

Analysed spending behaviour of responsive vs non-responsive customers

Analysed income differences between responsive vs non-responsive customers

Visualisation & Interpretation

Used bar charts to compare group-level averages

Focused on clarity and business interpretability

KEY ANALYTICAL QUESTIONS
1. Which campaign performed best?

Campaign performance was evaluated using acceptance counts and acceptance rates. This allowed comparison of effectiveness rather than raw volume alone.

2. Are higher-spending customers more responsive?

Customers were grouped into responsive and non-responsive segments, and their average total spending was compared.

3. Does income influence campaign acceptance?

Average income levels were compared between responsive and non-responsive customers to assess whether purchasing power plays a role in campaign success.

KEY INSIGHTS

Certain campaigns clearly outperform others in terms of acceptance, indicating that not all campaigns deliver equal value.

Customers who responded to at least one campaign tend to have higher average total spending, suggesting marketing efforts are more effective among high-value customers.

Responsive customers also show higher average income levels, indicating that income may influence campaign engagement.

BUSINESS RWECOMMENDATIONS

Prioritise high-performing campaigns and consider reallocating budget away from consistently low-performing ones.

Target high-spending and higher-income customer segments with tailored campaigns to maximise return on investment.

Use customer responsiveness and spending behaviour as key inputs for future campaign design and segmentation.

TOOLS AND TECHNOLOGIES.
SQL: Data cleaning, filtering, aggregation, validation

Python: Pandas, NumPy, Seaborn, Matplotlib

Jupyter Notebook: Exploratory data analysis and visualisation
