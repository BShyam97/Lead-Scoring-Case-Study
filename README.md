# Project Overview

X Education, an online education company, offers courses to industry professionals. Each day, numerous professionals visit their website, exploring various course offerings. The company promotes its courses across multiple platforms, including websites and search engines like Google. Visitors to the site may browse courses, fill out forms, or watch videos. When someone submits a form with their email address or phone number, they are classified as a lead. Additionally, leads are generated through referrals from previous customers. Once leads are captured, the sales team reaches out via phone calls, emails, etc. While some of these leads eventually convert into paying customers, the majority do not. Currently, the lead conversion rate at X Education is approximately 30%.

Despite generating a significant number of leads, X Education struggles with a low conversion rate. For example, out of 100 leads acquired in a day, only about 30 are converted. To improve efficiency, the company aims to identify high-potential leads, also known as "Hot Leads." By focusing their efforts on these promising leads, the sales team can potentially increase the conversion rate. The sales funnel starts with many leads at the top, but only a few become paying customers. Therefore, nurturing potential leads through education and consistent communication is crucial for improving the conversion rate.

X Education has tasked you with identifying the most promising leads—those most likely to convert into paying customers. Your goal is to build a model that assigns a lead score to each lead, indicating their likelihood of conversion. A higher lead score suggests a higher chance of conversion, while a lower score suggests a lower chance. The CEO has set a target conversion rate of around 80%.

# Data

The provided historical leads dataset contains around 9,000 data points. The dataset includes various attributes such as Lead Source, Total Time Spent on the Website, Total Visits, Last Activity, etc., which may influence whether a lead converts. The target variable in this dataset is 'Converted,' where 1 indicates a lead was converted, and 0 indicates it was not. You can find more details about the dataset in the data dictionary provided in the zip folder. Additionally, some categorical variables have a 'Select' level, which should be treated as a null value.

# Objective 
Build a logistic regression model that assigns a lead score between 0 and 100 to each lead. This score will help the company focus on potential leads, with higher (lower) scores indicating a higher (lower) likelihood of conversion.
