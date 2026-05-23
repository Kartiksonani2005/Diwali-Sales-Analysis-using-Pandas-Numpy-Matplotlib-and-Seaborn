Diwali Sales Data Analysis
Project Overview
This project performs Exploratory Data Analysis (EDA) on Diwali Sales data to uncover customer purchasing behavior and business insights.
The dataset contains transaction records including customer demographics, product categories, and sales amounts.

Tech Stack
Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

IDE: PyCharm / Jupyter Notebook

Data Preprocessing
Loaded dataset (Diwali Sales Data.csv) with 11,251 records.

Dropped irrelevant columns (Status, unnamed1).

Handled missing values in Amount.

Converted Marital_Status from numeric (0/1) to categorical (Unmarried, Married).

Exploratory Data Analysis (EDA)
1. Gender Analysis
Majority of buyers are female.

Purchasing power of females is higher compared to males.

2. Age Group
Most buyers belong to the 26–35 years age group.

Female buyers dominate this segment.

3. State‑wise Sales
Highest orders and sales from Uttar Pradesh and Maharashtra.

4. Product Categories
Clothing & Apparel has the highest number of orders.

Food category accounts for the highest spending.

5. Marital Status
Majority of buyers are married women.

6. Occupation
Most buyers work in IT, Healthcare, and Aviation sectors.

Key Insights
Diwali sales were driven mainly by young, married, working women.

Strong preference for clothing and apparel, while food attracted the highest spending.

Target audience for future campaigns: female professionals aged 26–35 from UP and Maharashtra.

Conclusion
This analysis highlights the importance of customer segmentation in retail marketing.
By focusing on demographics and spending patterns, businesses can design targeted strategies to maximize festive sales.

How to Run:

Clone the repository:
git clone https://github.com/<your-username>/Diwali-Sales-EDA.git

Install dependencies:
pip install pandas numpy matplotlib seaborn

Run the script:
python app.py
