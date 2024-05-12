# Modelling-Investor-Risk-Tolerance

## The project addresses the limitations of traditional risk tolerance questionnaires, which are often subject to errors due to behavioral biases and lack automation. By leveraging machine learning and detailed financial data, the project seeks to provide a more accurate and automated approach to determining an investor's risk tolerance, which is crucial for effective portfolio management.

Data Collection: The data comes from the Survey of Consumer Finances (SCF), conducted by the Federal Reserve Board. This survey provides detailed information about household demographics, net worth, financial, and nonfinancial assets for individuals in 2007 (pre-crisis) and 2009 (post-crisis). This data allows for an analysis of how household asset allocations changed after the 2008 global financial crisis.

Asset Categorization:
Risky Assets: These are investments in mutual funds, stocks, and bonds.
Risk-Free Assets: These include checking and savings balances, certificates of deposit, and other cash balances and equivalents.
Risk Tolerance Calculation:

Calculated the total assets of an individual by summing their risky and risk-free assets.
The ratio of risky assets to total assets is considered a measure of the individual’s risk tolerance. This ratio indicates how much risk an individual is willing to take on, with a higher proportion of risky assets suggesting higher risk tolerance.

Normalization of Risky Assets: The value of risky assets is normalized using the price of a stock index (like the S&P 500) between 2007 and 2009. This step adjusts for market value changes over time, providing a more accurate representation of risk tolerance.

Machine Learning Implementation: The project aims to build a supervised regression-based model to predict an investor's risk tolerance using demographic, financial, and behavioral attributes.
