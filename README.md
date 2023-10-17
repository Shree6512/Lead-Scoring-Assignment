# Lead_Scoring_Case_Study
## Problem Statement
A company in the education sector, known as X Education, offers online courses tailored to industry professionals. On a daily basis, numerous professionals with an interest in these courses visit the company's website to explore the available options.

X Education promotes its courses across various platforms, including websites and search engines like Google. When visitors arrive at the website, they often engage in actions such as browsing the course offerings, filling out course inquiry forms, or watching informative videos. Those who provide their contact information, such as email addresses or phone numbers, by filling out forms are classified as 'leads.' Additionally, the company accumulates leads through referrals from previous clients. Once these leads are in the company's possession, the sales team initiates outreach efforts, which may involve making phone calls, sending emails, and more. As a result of this outreach, some leads convert into paying customers, but the majority do not. X Education typically achieves a lead conversion rate of approximately 30%.

Despite the considerable volume of leads generated, X Education faces a challenge with a relatively low lead conversion rate. For instance, out of 100 acquired leads in a day, only about 30 end up converting into paying customers. To enhance the efficiency of this process, the company aims to identify the most promising leads, often referred to as 'Hot Leads.' Identifying this subset of leads could boost the lead conversion rate, as the sales team would then concentrate their efforts on communicating with the leads with the highest potential, rather than reaching out to every lead.

X Education has enlisted your expertise to assist them in selecting the most prospective leads, those most likely to become paying customers. The company requires you to develop a model that assigns a lead score to each lead. A higher lead score indicates a greater likelihood of conversion, while a lower score implies a lower chance of conversion. The CEO has set a target lead conversion rate of approximately 80%
## Data

You have been provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc., which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable is the column 'Converted', which indicates whether a past lead was converted or not (1 means converted, 0 means not converted). Please refer to the data dictionary provided in the zip folder for more information about the dataset.
One important aspect to consider is that many categorical variables have a level called 'Select', which needs to be handled as it is effectively a null value.

## Goals of the Case Study

1. Build a logistic regression model to assign a lead score between 0 and 100 to each lead. A higher score indicates a higher likelihood of conversion, while a lower score suggests a lower chance of conversion.

2. Address additional problems presented by the company, which your model should be able to handle. These problems are provided in a separate document and should be filled based on the logistic regression model developed in the first step. Ensure that you include this information in your final presentation.

Please refer to the respective documents and presentation for a comprehensive understanding of the case study and its outcomes.
