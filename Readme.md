# Loan Data Exploration


## Dataset
This dataset contains 113937 loansbased on 81 variables.  The data was downloaded from the udacity data archive through this link https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000

## Summary of Findings

In the exploration,
> I performed data wrangling on the data to check how tidy and clean the data was. The data was almost tidy as each row was an observation and each column was a variable, there were no duplicates also but there were to columns(Credit grade and prosperRating (Alpha)) that had to be joined.
> It was not clean however as the datatypes were not correct and there were so many missing values.I picked the variable of interest and picked variables thet would be necessary in the analysis. I cleaned the data while making sure not to lose so many data. 
> I made exploratory analysis on distribution of all the features I picked, I checked the distribution of all the variables and Their distribution in relation to themselves,I found that percentfunded variable had very weak correlations with other variables and this is because most of the loan observations had PercentFunded of 1.0.

> Outside of the main variables of interest, I saw high correlation between Recommendations and friends that invest

#### Challenges
> My variable of interest PerentFunded did not have strong correlation with the other variables. It might be better if more diverse data is collected as most of the observations had PercentFunding value of 1.0. Thus, it was difficult and required a lot of effort to see some patterns in the data.


## Key Insights for Presentation

For the presentation, I want to show variation in variables with percent funded and derive characteristics of loan observations with percentFunded

> Then, I checked variaton of categorical data and some numerical data with percentFunded.
I used boxplots to check the relationship between categorical data and percent funded and I was able to observe pattern I stated in the explanatory visualiztion slide.

> For the numerical data  and some categorical, I used a scatterplot and plotted with lenderyield and percentfunded to get more insights and stated the pattern observed in the slide.

