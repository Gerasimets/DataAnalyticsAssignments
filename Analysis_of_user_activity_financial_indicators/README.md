## Analysis of user activity and financial indicators

### Overview

The casino concept is based on the interaction between players and the casino, where players place bets and the casino pays out winnings based on certain rules. This README provides an overview of the metrics used in this analysis and the methodology used.

### Metrics

* Bet: The amount of funds the player has bet.
* Win: The amount of funds the player has won.
* GGR (Gross Gaming Revenue): Calculated as Bet - Win, indicating net wins (positive value represents profit for the operator, negative value represents loss).
* Margin % (House Edge): Calculated as GGR / Bet.
* Bonus: Funds paid out to the user by the operator as rewards or incentives.
* NGR (Net Gaming Revenue): Calculated as GGR – Bonus, providing the net profit.
* ARPU (Average Revenue Per User): Calculated as total revenue divided by the number of active users

### Methodology

- **Data preparation:** Python and its libraries (Pandas, Matplotlib, NumPy, Seaborn, Plotly) were used to preprocess and analyze the data set.
- **Exploratory Data Analysis:** Conducted preliminary analysis of user activity and financial indicators.
- **Visualization:** Created visualizations including:
  - DAU (Daily Active Users) Trends
  - Number of New Users by Market and Month
  - Correlation Analysis
  - Histogram of NGR by Bonus Status
  - Distribution of Different Values
- **Tableau Dashboard:** Created an interactive dashboard allowing users to explore:
  - Overall Metrics
  - DAU, NGR, and ARPU (Average Revenue Per User) by Date and City
  - Relationship Explorer showcasing correlations between different parameters.

### Additional Resources

[Link to Tableau Dashboard](https://public.tableau.com/views/Analysisofuseractivityandfinancialindicators/Overview?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

### Conclusion

This project provides analysis of user activity and casino financial performance. By examining key metrics such as GGR, NGR and user activity, stakeholders can gain valuable insight into a casino's performance and profitability. The Tableau dashboard includes interactive visualizations for deeper exploration.
