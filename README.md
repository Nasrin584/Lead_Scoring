# Lead_Scoring

**Problem Statement**
X Education, an online education company, offers courses tailored for industry professionals. Every day, numerous professionals visit their website, explore courses, and may engage with the content by watching videos or filling out inquiry forms.

The company promotes its courses through various digital platforms, including search engines like Google. When individuals submit their contact details through forms, they are classified as leads. Additionally, referrals from past customers contribute to lead generation. The sales team then reaches out to these leads via calls and emails, aiming to convert them into paying customers. However, the company currently experiences a lead conversion rate of only 30%.

Despite acquiring a large number of leads daily, only a fraction of them convert. For instance, out of 100 leads, only 30 proceed to purchase a course. To enhance efficiency, X Education aims to identify the most promising leads, termed Hot Leads. By prioritizing these high-potential leads, the sales team can focus its efforts more effectively, thereby increasing conversion rates. The lead conversion process can be visualized as a funnel, where a large pool of leads enters at the top, but only a select few successfully convert into paying customers. Proper nurturing—through continuous engagement and education—is crucial to improving conversion rates.

To optimize this process, X Education has tasked you with developing a model that assigns a Lead Score to each lead. This score will help rank leads based on their likelihood of conversion, allowing the sales team to prioritize high-scoring leads. The CEO has set a target lead conversion rate of approximately 80%.

**Dataset Overview**
The dataset consists of approximately 9,000 historical leads with various attributes, such as Lead Source, Total Time Spent on Website, Total Visits, and Last Activity. The objective is to analyze these features to determine their impact on lead conversion. The dataset includes a target variable, Converted, where:

1 indicates a successful conversion
0 indicates a lead that did not convert
Additionally, categorical variables contain a level labeled ‘Select’, which is equivalent to a missing value and needs to be handled appropriately.

**Goals of the Case Study**

This project aims to:

Develop a logistic regression model that assigns a lead score (ranging from 0 to 100) to help the company identify high-potential leads. A higher lead score signifies a higher likelihood of conversion, while a lower score indicates minimal conversion chances.
Ensure the model is adaptable to accommodate future business requirements, allowing X Education to adjust strategies dynamically.
Address additional business challenges outlined in a separate document, ensuring the model is robust and practical for real-world application.
The final presentation will include model insights, data-driven recommendations, and strategies to improve lead conversion rates efficiently.
