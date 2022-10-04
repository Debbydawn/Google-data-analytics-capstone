# Google-data-analytics-capstone
## Personal Story

This jounery started in Feburay 2022 when i took my first course in the Google Data Analytics Certificate titled Foundations: Data,Data,Everywhere, this course exposed
me to thinking like a data analyst and also the vary world od data as a whole. Moving on i went on to take the second course Ask Question to make Data-Driven Decision,
here i learnt how to ask effective question that can guide analysis, how to present findings, how to manage stakeholders with clear communication and also the ideas 
associated with structured thinking and how they help an analyst. Thirdly, Prepare Data for Exploration here i learnt how analysts decision based on which data to 
collect for the analysis, different types of data, how to use spreadsheets and SQl with databases, data ethics and an act of organizing data and keeping it safe.
Fourthly,Process Data from Dirty to Clean discover basic data cleaning techniques using spreadsheets, utilzing basic SQL queries for use in databases also exploring 
elements and importance of data cleaning reports. Fifthly, Analyze Data to Answer WEQuestions, i learnt how to orgqnize and fo4rmat your data in differnet ways, find out how to perform complex calculations on your data to complete business objectives using formulas, functions and SQL queries to conduct this analysis. Sixthly, Share Data Through the Art of Visualization, we were taught with the use of Tableau(a data Visualization platform) the importance of storytelling through data,how to use Tableau effectively and explored the principles and practice of effective presenattions.Seventhly, Data Analysis with R Programming, using R studio we learnt how to clean,organize, analyze, visualize and Report Data using R Markdown. Lastly, we were given 3 set of case studies to undertake, where i selected one and using Python i was able to examine, clesning and analyze the data to reflect the business goal of the company in the case study.

## Capstone Project (Bellabeat)

Bellabeat is a high-tech manufacturer of beautifully-designed health-focused smart products for women since 2013. Inspiring and empowering women with knowledge 
about their own health and habits, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for females.The co-founder and Chief 
Creative Officer, Urška Sršen is confident that an analysis of non-Bellebeat consumer data (ie. FitBit fitness tracker usage data) would eveal more opportunities 
for growth.

## Business Task:
Analyze FitBit Fitness Tracker Data to gain insights into how consumers are using the FitBit app and discover trends and insights for Bellabeat marketing strategy.

A good data source is ROCCC which stands for Reliable, Original, Comprehensive, Current, and Cited.

- Reliable - LOW - Not reliable as it only has 30 respondents
- Original - LOW - Third party provider (Amazon Mechanical Turk)
- Comprehensive - MED - Parameters match most of Bellabeat's products' parameters
- Current - LOW - Data is 5 years old and is not relevant
- Cited - LOW - Data collected from third party, hence unknown
- Overall, the dataset is considered bad quality data and it is not recommended to produce business recommendations based on this data.

From the above observation, noted that:
1. Obseverations
- There is no typo, Null or missing values.
- Data frame has 940 rows and 15 columns.
- ActivityDate is wrongly classified as object dtype and has to be converted to datetime64 dtype.
- There are 33 unique IDs, instead of 30 unique IDs as expected from 30 fitness tracker users.

2. Adjustment
- Converting ActivityDate from object to datatime64 dtype.
- Converting format of ActivityDate to yyyy-mm-dd. 
- Printing head to confirm whether it has been updated to datatime64 dtype and dates to yyyy-mm-dd.


## Analyzes

## Interpreting statistical findings:
- On average, users logged 7,637 steps or 5.4km which is not adequate. As recommended by CDC, an adult female has to aim at least 10,000 steps or
8km per day to benefit from general health, weight loss and fitness improvement. Source: Medical News Today article

- Sedentary users are the majority logging on average 991 minutes or 20 hours making up 81% of total average minutes.

- Noting that average calories burned is 2,303 calories equivalent to 0.6 pound. Could not interpret into detail as calories burned depend on several 
factors such as the age, weight, daily tasks, exercise, hormones and daily calorie intake. Source: Health Line article


## Recommendations based on our analysis.

Here, we revisit our business questions and share with you our high-level business recommendations.

- What are the trends identified?
Majority of users (81.3%) are using the FitBit app to track sedentary activities and not using it for tracking their health habits.
Users prefer to track their activities during weekdays as compared to weekends - perhaps because they spend more time outside on weekdays and stay in on weekends.

- How could these trends apply to Bellabeat customers?
Both companies develop products focused on providing women with their health, habit and fitness data and encouraging them to understand their current habits and 
make healthy decisions. These common trends surrounding health and fitness can very well abe pplied to Bellabeat customers.

- How could these trends help influence Bellabeat marketing strategy?
Bellabeat marketing team can encourage users by educating and equipping them with knowledge about fitness benefits, suggest different types of exercise 
(ie. simple 10 minutes exercise on weekday and a more intense exercise on weekends) and calories intake and burnt rate information on the Bellabeat app.

- On weekends, Bellabeat app can also prompt notification to encourage users to exercise.
