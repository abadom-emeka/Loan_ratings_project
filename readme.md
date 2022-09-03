# Prosper Loan Data Exploration

## Dataset

The data consists of information regarding 11393 loans. Each loan has 81 
variables(data on each loan). I selected 14 variables for investigation. 
The dataset was provided by Udacity.

## Summary of Findings

During exploration, I discovered relationship between among some variables. 
It appears that there is a negative relationship between borrowers rate and 
the prosper rating We see a rise in average borrowers rate as the ratings move
from best to worst. This implies that people with AA ratings get loans at the 
best rates. We observe lots of outliers on all the different categories of 
ratings. These outliers might point to the fact that ratings alone do not 
influence the borrowers rate.
Similarly, there is also a negative relationship between borrowers rate and 
score of loan applicants. Also, The average borrowers rate of defaulted loans 
is higher than completed loans.

Investigating the relationship among other variables produced some insights. 
Unsurprisingly,  he principal net loss increases as the ratings go from better 
to worse. We also notice  a constant drop in the average number of investors 
as we move from loan applications with the best ratings to the worst.


## Key Insights for Presentation

For the presentation, I use a vertical bar chart to show the top reasons why 
people take loans. Then I shifted my focus on visual that showed possible 
reasons for defaults on loans and the influence of ratings and score on loan 
investments. I displayed the relationship borrowers rate has with the two 
different ratings.

Then, I introduced more relationships with ratings. I used 
violin plots to show how how ratings could influence whether a loan would be 
fully paid or defaultedI plotted the average investors on the ratings. Looking further into the relationship between 
principal net loss and ratings, we added the income range variable. 
