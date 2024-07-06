
![finance-4858797_1280](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/56266b2b-f4a9-4e13-90ac-d9da5146631d)
# Loan-Analysis

## 1. Project Description :
The main aim of this project is to identify patterns that indicate if a customer will have difficulty paying their instalments. This information can be used to make decisions such as denying the loan, reducing the amount of loan, or lending at a higher interest rate to risky applicants. The company wants to understand the key factors behind loan default so it can make better decisions about loan approval.
The primary objective of this project is to utilize Exploratory Data Analysis (EDA) techniques to identify patterns within loan application data that indicate the likelihood of loan defaults.

## 2. Approach:
Downloaded and imported the dataset , performed data cleaning i.e. removing missing & invalid rows and handling outliers

## 3. Tech-Stack Used:
In this project, Microsoft Excel 2010 was used primarily for data analysis and visualization. The purpose of using Excel 2010 was to leverage its familiar interface. 
Overall, Microsoft Excel 2010 served as a versatile and accessible tool for conducting data analysis and visualization.
## 4. Insights:

###  A) Identify Missing Data and Deal with it Appropriately:

Identified missing data in the loan application dataset using Excel functions such as COUNT, ISBLANK, and IF. Implemented imputation techniques like AVERAGE or MEDIAN to handle missing values effectively.
Presented a bar chart illustrating the proportion of missing values for each variable, ensuring transparency in data quality assessment.
If the variable contains more than 50% null values then I have removed column

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/432cdfea-e9cb-4b3c-ae47-c2e365d4f37a)

### B) Identify Outliers in the Dataset:

Detected outliers in numerical variables of the loan application dataset utilizing Excel statistical functions QUARTILE, IQR, and conditional formatting. 
Applied business rules to distinguish valid outliers from anomalies requiring further investigation.so in amount_income_total and cnt_children at a point that are significantly different from the average or expected range in a statistical sample or division has clearly shown in following snapshot 
![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/80bfb6a8-0c17-413a-8f24-0395616fadc8)
![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/1ddb38a6-f3ab-4687-888b-e559466e09bc)

### C) Analyze Data Imbalance:
Conducted an analysis to ascertain data imbalance within the loan application dataset using Excel functions like COUNTIF and SUM. Calculated the ratio of data imbalance and visualized the distribution of the target variable through pie charts or bar charts, emphasizing any class imbalances. 
The ratio of imbalance data is 11.419.

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/3a8e5b32-a418-48cf-8442-9ed8b535ad31)
### D) Perform Univariate, Segmented Univariate, and Bivariate Analysis:

Executed comprehensive univariate analysis to comprehend the distribution of individual variables. 
Utilized segmented univariate analysis to compare variable distributions across different scenarios and performed bivariate analysis to explore relationships between variables and the target variable.

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/278ef7c5-7a28-48e3-8131-95a0161e4363)

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/9ba1e83e-8eaa-4d9d-ae4d-546f1d540eb4)

When considering the clients' education type, clients with secondary education are the ones who take loans most frequently, followed by clients with higher education. Clients with secondary/secondary special and lower secondary education are the ones who face payment difficulties.

When considering the clients' income type, working and commercial associates are the clients who take most of the loans. Working clients mostly have no payment difficulties, but there are also instances of payment difficulties within this category.

When considering the clients' housing type, most clients live in houses/apartments, and these clients mostly have no payment difficulties. Clients living with their parents, however, tend to have more difficulties in making loan payments.

When considering the clients' family status, married clients are the ones who take out more loans. Single/unmarried and civil marriage clients Experience higher payment difficulties.
When considering the clients' occupation type, labourers are the ones who take out the most loans. Security staff, drivers, cooking staff, low-skill labour, and waiter/bartender staff are the clients who face payment difficulties.

When considering the clients' credit amount, most clients with payment difficulties have loans ranging from 45,000 to 2,000,000.
![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/f090e750-3c77-4f18-8ee6-8522a59cc8c8)

### E) Identify Top Correlations for Different Scenarios:

Segmented the dataset based on various scenarios (e.g., clients with payment difficulties and all other cases) and identified top correlations for each segment using Excel functions such as CORREL. Ranked correlations to identify significant indicators of loan default within each scenario.
Presented correlation heat maps to visualize correlations between variables within each segment, employing different colours or shading to highlight top correlated variables and their relevance in predicting loan defaults

### Correlation for application with payment mode on time (0)

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/d41fb373-8056-40f4-93f0-e2d4b43820ba)

### Correlation for applicants with payment difficulties (1)

![image](https://github.com/AdityaaPujari/Loan-Analysis/assets/131788257/d11fecc1-379e-4ea9-88b0-b59464af8bc2)

## 5. Result:

In conclusion, the insights gathered from this project shed light on various aspects of loan applicants' characteristics and behaviors.The analysis of income totals revealed the presence of outliers, indicating individuals with significantly higher incomes compared to the majority. This highlights the importance of considering income disparity when assessing borrower risk and tailoring financial products to cater to different income levels. 

Overall, these insights contribute to a more nuanced understanding of loan applicants' characteristics, allowing financial institutions to develop tailored loan products, assess borrower risk more effectively, and provide inclusive financial solutions that cater to the diverse needs of their clients. By leveraging these insights, lenders can enhance their decision-making processes, promote responsible lending practices, and support the financial well-being of their customers.

> Links:
* Excel Links: https://docs.google.com/spreadsheets/d/1wTnUi9GTosytdV32x4pxwPy7MJRzPiMd/edit?usp=sharing&ouid=110939610603926904152&rtpof=true&sd=true
* Pdf: https://drive.google.com/file/d/1r8q8wNpByXBMlmPqQfe0Hxmp4iP0YdHq/view?usp=drive_link























