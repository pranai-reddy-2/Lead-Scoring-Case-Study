# Lead-Scoring-Case-Study


## Tools and Technology used:
<a href="https://www.javatpoint.com/classification-algorithm-in-machine-learning" rel="nofollow"><img alt="Classification" src="https://img.shields.io/badge/-Classification-f5841f?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-Classification-f5841f?style=for-the-badge" style="max-width: 100%;"/></a>
[![MATPLOTLIB](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge)](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge) [![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) [![Jupyter](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge)](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge) [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) [![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) <a href="https://seaborn.pydata.org/" rel="nofollow"><img alt="SEABORN" src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" style="max-width: 100%;"/></a> <a href="https://www.microsoft.com/en-in/microsoft-365/excel" rel="nofollow"><img alt="Excel" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" data-canonical-src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" style="max-width: 100%;"/></a>


## Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. A typical lead conversion process can be represented using the following funnel:

![XNote_201901081613670](https://user-images.githubusercontent.com/84577478/226532544-baa89462-befd-4a3b-bec1-919dd4cefb99.jpg)

As you can see, there are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

 X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.
 
## Goals of the Case Study
There are quite a few goals for this case study:

Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.


## Steps Followed
- Importing necessary libraries
- Importing the provided dataset
- Data Wrangling
- Exploratory Data Analysis (Variables Inspection)
- Data Preparation
- Model Building (Logistic Regression)
- Model Evaluation (Logistic Regression Metrics)
- Model Testing
- Model Inference
- Conclusion based on our results

## Conclusion:
- Landing Page Submissions and Lead Add Form lead to more conversions.
- Conversions are higher for leads from Google, Organic Search, Direct Traffic, and Referrals.
- SMS and Email marketing leads have higher conversions.
- Finance, HR, Marketing, Operations, and Banking sector leads tend to convert more.
- "Better Career Prospects" option for career outcome leads to higher conversions.
- Leads spending more time on the website tend to convert more.
- Reducing website bounce rate can increase customer engagement time and conversions.
- Lead Add Form generates qualifying leads and should be used across key areas.
- Sales team should focus on working professionals for higher conversions.
- Leads with a Lead Score >0.35 tend to convert more and model accuracy score is 91%
