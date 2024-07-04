Financial Reporting in Tableau - Part 1
In this tutorial, we will delve into the process of creating financial reports using Tableau, focusing on data import, modeling, and creating key financial metrics.

Step 1: Data Import
Data Source: Start by importing your data file (student.xlsx) into Tableau.
Data Linking: Link relevant sheets (e.g., calendar, GL by territory key, account key) using a many-to-one relationship for comprehensive data modeling and integration.


Step 2: Creating Reports

2.1 Profit & Loss Statement (P&L)
Summarize GL Amounts: Calculate the sum of amounts in GL and arrange by date.
Filter Data: Apply filters for country and subclass (select 'sale' for sales data).
P&L Structure:
Display amounts as text.
Arrange by chart of accounts (class).
Sort categories: trading, operating, non-operating, interest, and tax.
Further classify with subclasses: sales, cost of sales, operational expenses.


2.2 Gross Profit and Net Profit Calculation
Gross Profit: Summarize amounts by year and filter by trading amounts.
Net Profit: Duplicate the gross profit visualization and filter by interest and tax, non-operating, operating, and trading classes.


2.3 Operating Profit and Earnings Metrics
Operating Profit: Duplicate the net profit visualization and filter by trading and operating classes.
EBITDA (Earnings Before Interest, Tax, Depreciation, and Amortization):
Duplicate the operating profit visualization.
Filter by subclasses: operating expenses, sales, and cost of sales.


2.4 Profit Before Interest and Tax (PBIT)
PBIT Calculation: Duplicate the EBITDA visualization.
Filter Data: Refine by operational accounts, non-operational accounts, and trading accounts.


Conclusion
This tutorial has covered fundamental steps for creating financial reports in Tableau. In the next part, we will explore advanced calculations and formulas. Stay tuned for more insights and practical applications.
