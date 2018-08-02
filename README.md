# hr-ibm-attrition
Goal is how to reduce the attrotion rate In IBM

 I'll be working on the following:

• Quick EDA of some important variables, especially those related to income, promotion, performance and work-life balance,

• Trying to facilitate business decisions with implementing a comprehensible decision tree,
 Predicting  attrition rates using various algorithms 



Decision tree:
Prediction rate:
           
           No     Yes 
           
           813    69 

Variable importance: 

Age                               78.756856

JobLevel                          56.531879

JobRole                           63.803733

MonthlyIncome                     92.253753

TotalWorkingYears                 66.189112


Random forest:
Prediction rate:

No      Yes

767     115


Variable importance:
Age                                     36.182510

DailyRate                               30.917468

DistanceFromHome                        28.231360

JobRole                                 27.351452

MonthlyIncome                           42.794465

OverTime                                32.982346

TotalWorkingYears                       28.842850

HourlyRate                              26.765275


Gradient boosting algorithm:

Prediction rate:

No    Yes 

807     75 

Variable imporatance:

MonthlyIncome                    100.00

OverTimeYes                      89.32

Age                              54.23

EnvironmentSatisfaction          41.90

TotalWorkingYears                40.50



COMPARING MODELS:
By comparing these three models we can conclude that sensitivity of the decision tree is lower when comparing to other two models.

The top 5 factors that influence attrition are:

1. Monthly income

2. Age

3. Overtime

4. Total years of working

5. Job role

Other important factors:

1. Environment Satisfaction

2. Distance From Home

3. Hourly Rate

4. Daily Rate


Conclusions & Recommendations
• The main general reason behind attrition is most likely the effort-reward imbalance. In this case, this mostly applies to people who are working overtime and who in many cases have a relatively low salary - it should be checked whether there is an effective overtime policy in our company;

• Our simple decision tree shows that further solutions may not lie uniquely in people getting higher salaries (or their overtime pay). Those with relatively higher salaries may be interested in something more than just a paycheck, and might still leave if they do not feel part of the company (e.g. if they don't have any stock options, or if they don't have access to trainings);

• We have also found that different facets of work-life balance might represent an issue for our employees (a finding supported by visualizations and (at least to some extent) our best algorithm). One of the things that should be checked is e.g. whether there is a lack of certain teleworking arrangements in our company;

• There seems to be a link between attrition and age as well as the number of companies worked for. At this point, we cannot provide more information and it would be necessary to delve deeper into our dataset, e.g. to ascertain whether this is not simply linked to retirements or to see whether there is an unfair treatment of certain age groups and whether specific part of our workforce is in need of an intervention (e.g. more job security, upskilling, etc.).

• If we take our "test" set as an example of IBM's current workforce, we can say that the job role with highest probability of attrition is sales representative - something should be definitely done about that, and we could explore further what exactly.


