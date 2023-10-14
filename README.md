# ExtraaLearn-Project---Potential_Customers_Prediction
## Context
The EdTech industry has experienced significant growth in the past decade, with the Online Education market projected to be worth $286.62bn by 2023. The COVID-19 pandemic has further accelerated the growth of online education, attracting new customers and leading to the emergence of many new companies in the industry. ExtraaLearn is an initial stage startup that offers programs on cutting-edge technologies to students and professionals. With a large number of leads being generated, ExtraaLearn faces the challenge of identifying which leads are more likely to convert to paid customers. 

## Objective
As a data scientist at ExtraaLearn, your objective is to analyze the leads data and build a machine learning model to identify which leads are more likely to convert to paid customers. Additionally, you need to determine the factors that drive the lead conversion process and create a profile of the leads that are likely to convert.

## Data Description
The data provided contains various attributes of leads and their interaction details with ExtraaLearn. The data dictionary is as follows:

- ID: ID of the lead
- age: Age of the lead
- current_occupation: Current occupation of the lead (values: 'Professional', 'Unemployed', 'Student')
- first_interaction: How the lead first interacted with ExtraaLearn (values: 'Website', 'Mobile App')
- profile_completed: Percentage of profile filled by the lead on the website/mobile app (values: 'Low' - 0-50%, 'Medium' - 50-75%, 'High' - 75-100%)
- website_visits: Number of times the lead visited the website
- time_spent_on_website: Total time spent on the website
- page_views_per_visit: Average number of pages viewed during website visits
- last_activity: Last interaction between the lead and ExtraaLearn
- Email Activity: Details about program sought through email, information shared with lead (e.g., brochure of program)
- Phone Activity: Phone conversation or SMS conversation with representative
- Website Activity: Interaction on live chat with representative, profile updates on website, etc.
- print_media_type1: Flag indicating whether the lead saw the ad of ExtraaLearn in the Newspaper
- print_media_type2: Flag indicating whether the lead saw the ad of ExtraaLearn in the Magazine
- digital_media: Flag indicating whether the lead saw the ad of ExtraaLearn on digital platforms
- educational_channels: Flag indicating whether the lead heard about ExtraaLearn through education channels (e.g., online forums, discussion threads, educational websites)
- referral: Flag indicating whether the lead heard about ExtraaLearn through a reference
- status: Flag indicating whether the lead was converted to a paid customer or not
