# Business-Case-Study-Aerofit-Descriptive-Statistics-and-Probability
About Aerofit
Aerofit is a leading brand in the fitness equipment industry. The company offers a diverse range of products, including treadmills, exercise bikes, gym equipment, and fitness accessories, catering to the needs of a wide variety of customers.

Business Problem
Aerofit’s market research team aims to identify the characteristics of the target audience for each treadmill model to provide better recommendations for new customers. The goal is to analyze customer characteristics to uncover differences in product preferences and purchasing behavior.

Objective
Perform descriptive analytics to develop a detailed customer profile for each treadmill model in the Aerofit portfolio. This involves:

Constructing two-way contingency tables.
Computing marginal and conditional probabilities.
Generating insights and recommendations to guide business strategy.
Product Portfolio

KP281: Entry-level treadmill priced at $1,500.
KP481: Mid-level treadmill for runners, priced at $1,750.
KP781: Advanced treadmill with premium features, priced at $2,500.
Case Study Process

Data Import and Analysis

Import the dataset.
Analyze dataset structure and characteristics.
Outlier Detection

Use boxplots and descriptive statistics (e.g., difference between mean and median).
Feature Impact Analysis

Assess the impact of customer attributes like marital status and age on product preferences using count plots, histograms, and box plots.
Marginal Probabilities

Represent marginal probabilities, such as the percentage of customers purchasing KP281, KP481, or KP781, using tools like pandas.crosstab.
Correlation Analysis

Use heatmaps and pair plots to identify correlations among different factors.
Customer Profiling

Categorize customers by numerical attributes such as:
Age: young/old
Income: wealthy/middle income
Fitness: fit/not fit
Usage: regular/casual
Education: high/low
Leverage the crosstab function in pandas for customer segmentation.
Probability Analysis

Calculate marginal and conditional probabilities to find insights like the likelihood of a male customer buying a KP781 treadmill.
Recommendations and Insights

Provide actionable recommendations based on data-driven insights.
Recommendations

KP481: Market to middle-class females who want to run frequently.
KP281:
Target middle-class males and females who prefer light running.
Recommend to partnered females.
KP481: Recommend to single females.
KP281: Market to wealthy individuals (both males and females) for frequent running.
Fit individuals:
Recommend KP481 to fit males for lighter usage.
Recommend KP281 to fit females for lighter usage.
Casual users: Recommend KP281 or KP481.
Regular fit users: Recommend KP781.
Regular unfit users: Recommend KP281 or KP481.
Middle-income unfit individuals: Recommend KP281.
Wealthy individuals:
Fit individuals: Recommend KP781.
Unfit individuals: Recommend KP481.
Middle-income fit females: Recommend KP481.
Code Repository
The detailed analysis and implementation are available in the Jupyter Notebook.
