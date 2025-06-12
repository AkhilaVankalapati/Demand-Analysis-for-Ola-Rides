# Demand Analysis for Ola Ride Bookings

# Overview

Ola, is one the India’s leading micro-mobility service provider, offers for daily commuting. Recently, the company has observed significant ride bookings  and seeks to understand the key factors influencing the demand for ride bookings in the Indian market. This project aims to analyze various factors that affect demand, offering insights into which variables significantly impact usage and how these variables interact.

# Data Set information

This Data Set Includes the following information.

- **Datetime** :: Timestamp of the data record.
- **Season** :: Season of the year (1: Spring, 2: Summer, 3: Fall, 4: Winter).
- **weather**:: Weather condition code (1 to 4, where 1 is Clear and 4 is Severe).
- **temp**:: Actual temperature in Celsius.
- **humidity**:: Humidity level (%).
- **windspeed**::Wind speed.
- **casual**:: Number of casual users.
- **registered**:: Number of registered users.
- **count**:: Total number of electric cycles rented (dependent variable).

# Steps Taken

# Data Import and Exploration:

- Load the dataset and perform exploratory data analysis (EDA) to understand the structure, characteristics, and distribution of the data.
- Visualize data to identify patterns and outliers.

# Hypothesis Testing:

- Establish relationships between the dependent variable (count) and independent variables (workingday, weather, season, etc.).
- Formulate null and alternative hypotheses for each factor under consideration.
- Select and apply appropriate statistical tests such as:
    - **2-sample t-test**: To assess the effect of working days on rental counts.
    - **ANOVA**: To evaluate differences in cycle rentals across seasons.
    - **Chi-square test**: To check the dependency between weather and season.

# Statistical Assumptions and Tests:

- Verify assumptions for normality and equal variance using visual tools like histograms and Q-Q plots or statistical methods (Levene’s test, Shapiro-Wilk test).
- Proceed with the analysis even if assumptions are violated but make sure to document and report these findings.

# Significance Testing:

- Set the significance level (α) for hypothesis testing.
- Calculate test statistics and decide whether to accept or reject the null hypothesis.
- Draw inferences based on the statistical analysis.

# Modeling and Interpretation:

- Explore potential predictive models to quantify the impact of significant variables on demand.
- Interpret the results to provide actionable insights for Ola.

# Tools and Technologies:

- **Programming Language**: Python (Pandas, NumPy, SciPy, Statsmodels)
- **Visualization**: Matplotlib, Seaborn
- **Statistical Testing**: SciPy, Statsmodels

# Deliverables

- **Codebase**: Python scripts for data analysis and hypothesis testing.
- **Final Report**: Detailed report on the factors affecting the demand for ola's Ride Bookings, including statistical test results and business recommendations.

# Conclusion

This project aims to identify and analyze the factors driving demand for Ola Ride Booking, providing data-driven insights to help the company improve its service offerings and address revenue challenges.


