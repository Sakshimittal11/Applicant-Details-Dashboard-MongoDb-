 ## **Analysis of Applicant Details for loan approval**

This repository contains Visulizations created using MongoDB Atlas.


# **Introduction**

The Loan Applicants Dataset offers a comprehensive view of individuals applying for loans, focusing on financial stability, demographic factors, and the likelihood of defaulting. Each record includes crucial details such as the applicant's age, annual income, occupation, employment history, and loan default risk. Additional attributes like house ownership, vehicle ownership, marital status, and geographic data enrich the dataset, enabling a holistic analysis of applicant profiles.


The dataset provides valuable insights into the socio-economic factors influencing loan approval and repayment behaviors. For instance, the analysis can uncover patterns linking employment stability and income levels to default risk or reveal how demographic attributes such as age, marital status, or residence affect financial decision-making. Furthermore, geographic trends can highlight regional disparities in loan performance, while occupation-based insights can guide targeted credit strategies.This dataset is a powerful tool for financial institutions aiming to minimize default risks, design tailored financial products, and optimize loan approval processes. Advanced analytics can also support predictive modeling to identify high-risk applicants, offering actionable insights for data-driven decision-making.


**Dataset Attributes**

1.Applicant_ID - Unique identifier for each loan applicant.

2.Applicant_Age - Age of the applicant (grouped into ranges).

3.Annual_Income - Annual income of the applicant in monetary terms.

4.Occupation - Profession or job category of the applicant (e.g., Physician, Engineer).

5.Years_in_Current_Employment - Duration (in years) that the applicant has been in their current job.

6.Loan_Default_Risk - Binary indicator of whether the applicant has a high risk of defaulting on the loan (1 for default, 0 for no default).

7.House_Ownership - Housing status of the applicant (e.g., rented, owned).

8.Vehicle_Ownership - Whether the applicant owns a vehicle (yes/no).

9.Years_in_Current_Residence - Number of years the applicant has lived in their current residence.

10.Residence_City - City of residence for the applicant.

11.Residence_State - State of residence for the applicant.

12.Marital_Status - Marital status of the applicant (married/single).


**Dashboard**



![Sakshi Mittal - 045049 Dashboard](https://github.com/user-attachments/assets/df49658b-5d85-4e19-a942-c71d884388d6)




**Charts**

**1. Work Experience with Annual Income by Loan Default Risk**

This chart visualizes the relationship between annual income and work experience across different levels of loan default risk. Applicants are grouped based on their years of employment.

Question:
How does annual income correlate with work experience and loan default risk?

Key Observations:

1.Applicants with higher work experience tend to have higher annual incomes.

2.Lower-income groups show a higher likelihood of defaulting.

3.Long-term employees (10+ years) exhibit fewer defaults, highlighting financial stability.


Notable Patterns:

1.Longer work experience often correlates with reduced loan default risk due to stable income levels.

2.Lower work experience groups show greater variation in default risk.

Insights:

Loan eligibility criteria could prioritize applicants with longer work experience and stable incomes.

**2.  Loan Default Risk by Occupation**


This chart shows the distribution of loan defaults across various occupations, highlighting the number of defaulters (1) and non-defaulters (0) for each job type.

Question:
Which occupations are most or least likely to default on loans?

Key Observations:

1.Stable professions like "Physician" and "Psychologist" have lower default rates.

2.Creative roles, such as "Comedian" and "Web Designer," show higher default risks, likely due to irregular incomes.

3.Some fields, like "Teacher" and "Civil Engineer," have balanced default rates.

Notable Patterns:

1.High-income and stable jobs tend to reduce default risks.

2.Creative professions face greater financial challenges, leading to higher defaults.

Insights:

Financial institutions could adapt loan policies by factoring in occupation-based income stability and risks. 

**3. Employment Stability by Loan Default Risk**

This bar chart highlights the relationship between years in current employment and loan default risk.

Question:
How does employment stability influence loan repayment behavior?

Key Observations:

1. Applicants with 5+ years in current employment show significantly lower default rates.
   
2. Default risk is highest among those with 0–2 years of employment.

Notable Patterns:

1. Employment stability reduces default risks, indicating income consistency.

2. Early-career applicants face greater financial challenges.

Insights:

Lenders may consider employment tenure as a key factor when assessing loan applications.

**4. Loan Applicants by City**

A donut chart categorizes applicants based on their residence city to examine regional distribution.

Question:
Which cities contribute most to the applicant pool?

Key Observations:

1. The highest number of applicants comes from urban cities like "City A" and "City B."

2. Rural cities contribute fewer applicants, indicating limited access to financial services.
   
Notable Patterns:

1. Urban areas dominate loan applications due to higher population density and awareness of loan facilities.

Insights:

Banks could focus outreach efforts in rural areas to expand their customer base.

**5. Comparing Average Annual Incomes Across Occupations**

This bar chart shows the average annual income across various occupations.

Question:
Which occupations report the highest and lowest average incomes?

Key Observations:

1. Occupations like "Physician" and "Psychologist" have the highest average incomes.
   
2. Creative roles like "Comedian" report significantly lower incomes.
   
Notable Patterns:

1. High-income professions are typically in specialized or technical fields.

2. Creative roles reflect wider income disparities.

Insights:

Income-based risk analysis could help lenders improve their credit-scoring models.

**6. Occupation by Years in Current Employment**

A word cloud visualizes the frequency of different occupations by employment duration.

Question:
Which occupations dominate among applicants with varying employment tenures?

Key Observations:

1. "Physician" appears most frequently, indicating long-term stability in the medical field.
   
2. Creative professions like "Comedian" appear less frequently, reflecting career variability.
   
Notable Patterns:

1. Occupations tied to specialized skills tend to have consistent employment durations.

Insights:

Understanding dominant occupations could help banks tailor financial products to specific groups.

**7. Comparative Analysis of Average Annual Income by Residence State**

This line chart compares average incomes across different states.

Question:
Which states report the highest and lowest incomes?

Key Observations:

1. States like "State X" have the highest average incomes.
   
2. Income levels vary widely between states, with "State Y" reporting the lowest.
   
Notable Patterns:

1. Wealthier states show better income consistency across applicants.

Insights:

Targeting wealthier regions for premium financial products could enhance profitability.


**8. Default Risk for Long-term Employees**

A KPI metric showing the overall default rate among long-term employees.

Question:
What is the loan default risk for applicants with extensive employment tenure?

Key Observations:

1. The default rate is minimal among long-term employees, indicating strong financial reliability.
   
Notable Patterns:

1. Longer employment directly correlates with reduced loan default risks.

Insights:

Encouraging long-term employment applicants can help reduce default rates.

**9. Experience Distribution of High Earners**

This gauge chart represents the percentage of applicants with high annual incomes and significant work experience.

Question:
What percentage of applicants belong to the high-earner category with extensive work experience?

Key Observations:

1. A small but significant portion of applicants fall into this category.

2. These applicants are less likely to default on loans.
   
Notable Patterns:

1. High-income applicants generally have extensive work experience, reducing financial risks.

Insights:

Lenders can prioritize high earners with strong work experience for premium loan offerings.


**10. An Insight into Number of Applicants across Residence City**

A stacked bar chart shows the number of applicants grouped by years in current residence, segmented by city.

Question:
How does the number of applicants vary by residence city and duration of stay?

Key Observations:

1. Urban cities have higher applicant volumes with varying durations of residence.
   
2. Stability in residence is more common in smaller cities.
   
Notable Patterns:

1. Frequent movers are more common in urban centers, reflecting a dynamic lifestyle.

Insights:

Residence stability can be used as a secondary indicator of financial reliability.

**11. Count of Applicants by House Ownership**

This bar chart illustrates the count of applicants based on their house ownership status and loan default risk.

Question:
How does house ownership impact loan default risk?

Key Observations:

1. Applicants who own houses have lower default rates.
   
2. Non-homeowners show higher loan default risks.
   
Notable Patterns:

1. Owning a house signals financial stability and reduces default risks.

Insights:

House ownership can be a strong predictor of loan repayment behavior.


**Insights from Dashboard:**

1. Work and Financial Patterns: Applicants with longer work experience tend to have higher annual incomes. However, loan default risk remains present across all income brackets, though higher for lower-income groups.
2. Occupation Trends: Specific occupations like "Physician" and "Comedian" show contrasting loan default risks, indicating varied financial stability within job categories.
3. Geographic Insights: Urban centers have higher loan applicants, with cities like "Mumbai" and "Delhi" dominating. Average incomes are highest in industrialized states.
4. Housing and Ownership Patterns: House owners show lower default risk compared to renters, signaling stability in financial standing.
5. Loan Risk and Stability: Applicants with longer employment tenure exhibit lower default risks, emphasizing the role of job stability.
6. Demographic Observations: Young applicants (20-30 years) are the largest group seeking loans, but their risk is higher compared to older, financially stable groups.


**Managerial Implications:**

1. Risk Mitigation Strategies: Banks should focus on offering customized loan products for applicants with lower incomes and unstable job tenure while mitigating risk using predictive models.
2. Targeted Marketing: Financial products could be tailored based on demographic data. For instance, younger applicants could benefit from educational or career-based loans.
3. Regional Prioritization: Cities with high-income groups can be targeted for premium financial services, while areas with high default risks require stricter underwriting standards.
4. Data-Driven Decision Making: The integration of insights from applicants' housing, occupation, and income data enables robust creditworthiness evaluations.
5. Product Innovation: Introducing job stability incentives, such as reduced interest rates for long-term employees, could attract stable borrowers.
   
This dashboard provides a comprehensive understanding of financial and demographic variables, allowing decision-makers to design data-backed strategies for minimizing risk and optimizing financial inclusion.Applicant Details
