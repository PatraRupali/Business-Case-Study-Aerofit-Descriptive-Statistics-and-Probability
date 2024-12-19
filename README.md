# Business-Case-Study-Aerofit-Descriptive-Statistics-and-Probability

# About Aerofit  
Aerofit is a leading brand in the fitness equipment industry. The company offers a diverse range of products, including treadmills, exercise bikes, gym equipment, and fitness accessories, catering to the needs of a wide variety of customers.

## Business Problem  
Aerofit’s market research team aims to identify the characteristics of the target audience for each treadmill model to provide better recommendations for new customers. The goal is to analyze customer characteristics to uncover differences in product preferences and purchasing behavior.

## Objective  
Perform descriptive analytics to develop a detailed customer profile for each treadmill model in the Aerofit portfolio. This involves:  
1. Constructing two-way contingency tables.  
2. Computing marginal and conditional probabilities.  
3. Generating insights and recommendations to guide business strategy.

## Product Portfolio  
1. **KP281**: Entry-level treadmill priced at $1,500.  
2. **KP481**: Mid-level treadmill for runners, priced at $1,750.  
3. **KP781**: Advanced treadmill with premium features, priced at $2,500.

## Case Study Process  
1. **Data Import and Analysis**  
   - Import the dataset.  
   - Analyze dataset structure and characteristics.

2. **Outlier Detection**  
   - Use boxplots and descriptive statistics (e.g., difference between mean and median).

3. **Feature Impact Analysis**  
   - Assess the impact of customer attributes like marital status and age on product preferences using count plots, histograms, and box plots.

4. **Marginal Probabilities**  
   - Represent marginal probabilities, such as the percentage of customers purchasing KP281, KP481, or KP781, using tools like `pandas.crosstab`.

5. **Correlation Analysis**  
   - Use heatmaps and pair plots to identify correlations among different factors.

6. **Customer Profiling**  
   - Categorize customers by numerical attributes such as:  
     - Age: young/old  
     - Income: wealthy/middle income  
     - Fitness: fit/not fit  
     - Usage: regular/casual  
     - Education: high/low  
   - Leverage the `crosstab` function in pandas for customer segmentation.

7. **Probability Analysis**  
   - Calculate marginal and conditional probabilities to find insights like the likelihood of a male customer buying a KP781 treadmill.

8. **Recommendations and Insights**  
   - Provide actionable recommendations based on data-driven insights.

## Recommendations  

### Target Customers for Each Product:  

1. **KP281** (Entry-level treadmill):  
   - Middle-class males and females who want to run less.  
   - Partnered females.  
   - Casual users (whether fit or not).  
   - Regular users (males and females) who are not fit.  
   - Middle-income unfit individuals.  

2. **KP481** (Mid-level treadmill):  
   - Middle-class females who want to run more.  
   - Single females.  
   - Fit males who want to use the treadmill less.  
   - Wealthy individuals (both males and females) who want to run more.  
   - Wealthy individuals who are not fit.  
   - Middle-income fit females.  

3. **KP781** (Advanced treadmill):  
   - Fit individuals (males and females) who want to use it regularly.  
   - Wealthy, fit individuals.  

### General Insights:  
- Casual users, whether fit or not, should be recommended **KP281** or **KP481**.  
- Fit males and females with light usage should be guided toward **KP481** or **KP281**, respectively.  
- Regular fit users should opt for **KP781**.  




