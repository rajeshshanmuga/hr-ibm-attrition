# hr-ibm-attrition
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



COMPARING MODELS





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



Conclusion:

When we concentrate on top 5 factors we can lower the rate of attrition in feature.


