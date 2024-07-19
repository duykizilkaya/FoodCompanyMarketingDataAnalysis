# Food Marketing Data Analysis Project

** German Below


This project involves the comprehensive analysis of marketing data from a food company. The primary objective is to gain insights into customer behavior, spending patterns, and responses to various marketing campaigns to optimize future marketing strategies.

## Project Overview

### Goals:

* Data Cleaning and Transformation: Prepare the data for analysis by handling missing values, converting data types, normalizing columns, dealing with outliers, and renaming columns for better readability.
* Descriptive Analysis: Summarize the main features of the dataset, including customer demographics, their spending habits, and their responses to campaigns to understand the overall data distribution.
* Exploratory Analysis: Use visual and statistical techniques to uncover patterns, correlations, and trends within the data, providing a deeper understanding of customer behavior.
* Visual Analysis: Create visualizations to illustrate key trends and patterns in the data, making it easier to interpret and communicate findings.
* Statistical Analysis: Conduct statistical tests, such as chi-square tests and point-biserial correlations, to validate findings and uncover deeper insights.
* Actionable Insights: Generate actionable insights and recommendations based on the analysis to improve marketing strategies and customer targeting.

### Achievements:

* Cleaned and transformed the dataset for effective analysis.
* Generated a variety of visualizations to illustrate key insights.
* Performed statistical analyses, including chi-square tests and point-biserial correlations, to support findings.

### Results:

_Visual Results_:

The project includes several visualizations to highlight key findings. Here are some examples below:

* Proportion of response to the last campaign
![download](https://github.com/user-attachments/assets/cd3aebb0-2c43-40ce-ab3f-736a49b899ae)

* Proportion of total acceptance of campaigns by marital status
![download](https://github.com/user-attachments/assets/e650ecb8-1ddd-414c-9f92-1032ee3135cc)

* Proportion of total acceptance of campaigns by education level
![download](https://github.com/user-attachments/assets/4de94b4a-8022-4464-b8ce-6629ef66fe8b)

* Proportion of positive responses to the last campaign by age
![download](https://github.com/user-attachments/assets/63bf5fb7-d560-4a37-aeba-4729bfec58a3)

* Proportion of positive responses to the last campaign by income
![download](https://github.com/user-attachments/assets/912eca3a-79b8-47c1-9193-4d62e066ea88)

* Proportion of complaints for the last two years
![download](https://github.com/user-attachments/assets/f84c0e3e-c027-41b1-a12d-af07fde30a1c)

* Number of purchases from deals for different income levels, split by whether the customer has complaints
![download](https://github.com/user-attachments/assets/5a96041a-ff67-4915-84d3-d5dc63bf101e)

* Relationship between purchases made with discount and directly in store
![download](https://github.com/user-attachments/assets/05159312-b0b7-4aeb-a926-fd999c7a5947)

* Relationship between yearly income and purchases directly made in store
![download](https://github.com/user-attachments/assets/5536c569-7de5-4eca-90dc-ecb451eedf15)

* Correlation Map by using Heatmap
![download](https://github.com/user-attachments/assets/bcfa3937-3232-422b-8950-5740569d1c56)

* Normal distribution of online purchases by using Box-Cox
![download](https://github.com/user-attachments/assets/8af991ad-cee6-4600-bba1-c485af9559c3)


_ Statistical Analysis Results:_


* Chi Square test between marital status and total acceptance of campaigns
    * Results:
      * Chi-square statistic: 21.999964751929234 P-value: 0.34051255512614115 Degrees of freedom: 20
      * Interpretation: There is no statiscally significant relationship between marital status and total acceptance of campaigns.
     
* Chi Square test between marital status and response to the last campaign.
    * Results:
      * Chi-square statistic: 49.75615728266045, P-value: 4.059941296120542e-10, Degrees of freedom: 4
      * Interpretation: There is a statiscally significant relationship between narital status and response to the last campaign.
        
* Chi Square test between education level and total acceptance of campaigns.
    * Results:
      * Chi-square statistic: 26.49211391787158, P-value: 0.1501670313163349, Degrees of freedom: 20
      * Interpretation: There is no statiscally significant relationship between education and total acceptance of campaigns.

* Chi Square test between education level and response to the last campaign.
    * Results:
      * Chi-square statistic: 23.991956593084325, P-value: 8.017183023481722e-05, Degrees of freedom: 4
      * Interpretation: There is a statiscally significant relationship between education level and response to the last campaign.

* Point-Biserial Correlation between customer tenurity and response to the last campaign
    * Results:
      * Point-Biserial Correlation: 0.19566454820877288, P-value: 1.855325294014346e-20
      * Interpretation: There is a statiscally significant relationship between customer tenurity and response to the last campaign
 
*  Point-Biserial Correlation between age and response to the last campaign
   * Results:
      * Point-Biserial Correlation: -0.019913214819125384, P-value: 0.3500854366111601
      * Interpretation: There is no statiscally significant relationship between age and response to the last campaign

*  Point-Biserial Correlation between age and total acceptance of the campaigns
   * Results:
      * Point-Biserial Correlation: -0.005788568243497362, P-value: 0.7859274926457515
      * Interpretation: There is no statiscally significant relationship between age and total acceptance of the campaigns
    
*  Point-Biserial Correlation between yearly income and total acceptance of the campaigns
      * Point-Biserial Correlation: -0.005788568243497362, P-value: 0.7859274926457515
      * Interpretation: There is a statiscally significant relationship between yearly income and total acceptance of the campaigns
  

### Key Findings

* Customer Demographics: The majority of customers are middle-aged, with a significant portion of customers aged between 35 and 55. Income distribution shows that most customers earn between $30,000 and $60,000 annually.

* Spending Patterns: Customers spend the most on wines, followed by meat products. This indicates a preference for these categories. Spending habits vary significantly across different education levels and marital statuses.

* Campaign Responses: Response rates to the last campaign vary by marital status and education level, with married and higher-educated individuals showing more positive responses.

### Conclusion

The analysis of the food marketing data has provided several valuable insights that can inform future marketing strategies:

* Target High-Spending Categories: Focus marketing efforts on promoting wines and meat products, as these are the categories with the highest customer spending.

* Segmented Marketing Campaigns: Tailor marketing campaigns based on marital status and education level, as these factors significantly influence campaign responses. For instance, campaigns targeting married and higher-educated individuals are likely to be more effective.

* Customer Engagement: Invest in strategies to engage long-tenure customers, as they show a positive response to campaigns. Loyalty programs or exclusive offers could be effective.

* Addressing Customer Complaints: Implement measures to reduce customer complaints, as dissatisfaction significantly affects campaign responses. Improved customer service and prompt resolution of issues are essential.

* Income-Based Marketing: Although yearly income showed mixed results in terms of campaign acceptance, higher-income customers are generally more responsive. Consider premium offerings and exclusive deals for higher-income segments.

* Age Consideration: While age did not show a significant impact on campaign responses, it is still useful to consider age-specific preferences when designing product offerings and marketing messages.

By leveraging these insights, the food company can optimize its marketing strategies, improve customer satisfaction, and increase overall campaign effectiveness. The combination of descriptive, exploratory, and statistical analyses has provided a comprehensive understanding of customer behavior and preferences, which is crucial for making informed marketing decisions.

