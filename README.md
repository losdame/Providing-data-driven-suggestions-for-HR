# Employee Leave Prediction

## Overview

The goal of this project was to develop predictive models using multiple linear regression and Random Forest techniques to determine whether or not an employee will leave Salifort Motors. The analysis utilized data collected over ten years by the Human Resources Department. The final Random Forest model achieved an AUC of 93.84%, precision of 87%, accuracy of 96%, F1-score of 88%, and recall of 90.36%. The analysis revealed that features such as the last evaluation, number of projects, tenure, and overworking were most influential in predicting employee departures.

## Business Understanding

The HR department at Salifort Motors aims to improve employee satisfaction and retention. Although they have collected extensive data on employees, they need guidance on how to utilize this information effectively. As a data analytics professional, you were tasked with providing data-driven insights to answer the critical question: What factors are likely to make an employee leave the company?

## Data Understanding

The dataset provided by the Human Resources Department of [Salifort Motors](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) contains approximately 15,000 records and 10 features. These features include satisfaction level, number of projects, promotions over the last 5 years, and whether the employee left the company. 

*Note: The bar chart below illustrates the distribution of employees who left versus those who stayed.*

![image-3.png](attachment:image-3.png)

The data was cleaned by removing redundant columns and converting features to the appropriate data types.

## Modeling and Evaluation

A Random Forest model with 100 decision trees was employed to determine feature importance and predict employee turnover. The model's performance metrics are as follows:
- **Accuracy**: 96%
- **Precision**: 87%
- **Recall**: 90.36%
- **F1-Score**: 88%
- **AUC**: 93.84%

*Note: The plot below shows that the last evaluation, number of projects, and tenure were identified as the top three most important factors in predicting employee departures.*

![image-2.png](attachment:image-2.png)

## Conclusion

The analysis confirms that overworking is a significant factor contributing to employee turnover at Salifort Motors. To improve retention, the following recommendations are suggested:

- **Cap the Number of Projects**: Limit the number of projects an employee can handle to prevent overwork.
- **Promotion Review**: Consider promoting employees who have been with the company for at least four years, or investigate why long-tenured employees may be dissatisfied.
- **Manage Work Hours**: Either reward employees for working long hours or adjust expectations to reduce workload.
- **Communicate Overtime Policies**: Ensure that employees are aware of the company’s overtime pay policies and clarify expectations around workload and time off.
- **Enhance Company Culture**: Conduct discussions to understand and address company culture both broadly and within specific teams.
- **Reward Proportionately**: Implement a reward system that recognizes employees' contributions and efforts in a fair and proportionate manner, rather than solely based on hours worked.

This project provides actionable insights that can help the HR department at Salifort Motors to implement effective strategies for improving employee satisfaction and retention.
