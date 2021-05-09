# Titanic_Kaggle

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, 
killing 1502 out of 2224 passengers and crew. 
This sensational tragedy shocked the international community and led to better safety regulations for ships.
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. 
Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others,
such as women, children, and the upper-class.

In this challenge, the complete analysis of what sorts of people were likely to survive. 
In particular, Here the tools of machine learning is applied to predict which passengers survived the tragedy.

# Findings From EDA

- Females Survived more than Males.
- Passengers Travelling in Higher Class Survived More than Passengers travelling in Lower Class.
- Name column is having all unique values so this column is not suitable for prediction, we have to drop it.
- In First Class Females were more than Males, that's why Fare of Females Passengers were high.
- Survival Rate is higher for those who were travelling with siblings or spouses.
- Passengers travelling with parents or children have higher survival rate.
- Ticket column is not useful and does not have an impact on survival.
- Cabin column have a lot of null values , it will be better to drop this column.
- Passengers travelling from Cherbourg port survived more than passengers travelling from other two ports.

# The Result is stored in General_submission.csv
