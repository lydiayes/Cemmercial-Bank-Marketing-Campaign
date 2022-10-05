
Agenda Part 1- Client Demigraphicpart 2- Results from the Last Campaignpart 3- Analysing Part 4- Discussion and Recommendationpart 5- Q & A

Part 1- Client Demographic
The purpose of today's discussion is to share predicting insights of our potential client from the last campaign.Before we dig into that, let's do a recap of the client demographic.
Focusing group on Variable - y - has the client subscribed to a term deposit? ("yes","no")
 

Part 2- Results from the Last Campaign
This is the outcome of the previous campaign Within a total of 42600 people.There are about 10% subscribed to our products (term deposit).Since our discussion purpose is to look into the factors that encourage people to subscirbe to our products.For the rest of the discussion, we will be focusing on the 4200 subscribers.
 


Part 3- Analysing
Models On PythonDownload files on: https://github.com/lydiayes/Cemmercial-Bank-Marketing-CampaignWe first checked on missing data and missing cells, missing values in the training dataset. Amount 17 variable, we focus on our target group, Y is the target variable While 'no' means the client did NOT subscribe to a term deposit While 'yes' means the client subscribed to a term deposit
 

 
From the following analyzing result, it is clearly shown that
1- Age range for subscribers are higher than non-subscribers. 2- Bank statement Balances of subscribers are higher than non-subscribers. 3- Subscribers contacts about 1-day fasters than non-subscribers. 4- The average duration of the last contact is 2.6 times higher in the subscription group.
Interestingly, on the other hand, the number of days that passed after the last contact with the client, from a previous campaign is smaller

1- Average days of users who purchased financial products (days since last contacted the customer) 2- The campaign should be less than the average days of non-purchasing users, which is reasonable because the smaller the pdays 3- The closer the day of the last call, the stronger the user's memory of financial products, and therefore the greater the chance of sales. 4- If the average campaign of users who purchase financial products (the number of phone calls with users) 5- Similarly, the average campaign of users who have not purchased.


 

Relative to Job Variables for conclusion:1- It is clear to see that the number of term deposits is various by work. 2- Management is the top buyers, but the non-subscribers are ranking second. 3- Numbers in blue-collar, admin are relatively large.

 
1- Marital status doesn't show strong relative to subscribers' preference. 2- Single/Divorced people are more likely to make a term deposit.

 

 During the holiday season, December, it is unlikely for people to make a term deposit.

 


Models On RDownload files on: https://github.com/lydiayes/Cemmercial-Bank-Marketing-Campaign1- Using Random Forest Model for the machine learning algorithm.2- Combing the 17 variables decision trees.3- Evaluate the total trees for taking a majority vote.4- The greater the trees in the random Forest Model, the more acturaly perdiction will be.
Example Trees Shown below:

 



Part 4- Recomandation
 
  *****There is a huge opportunity for management and technician, who has the potential willing to subscribe and has cell-phone.
For the business strategy, people who have less than 100 dollars in the bank account is actually in the management industry. This means, people has high incomes that might have the possibility to own several bank accounts. We will try to contact with people who has less balance in the bank account to transfer their term deposit from other bank to our bank. With biger picutres, we are not only going to focust on the client who has a lot of balance in our current deposit account. People who age between 20-30 and singel is one target group, due to they don't have family pressure. People who age above 50 and divorce is another target group, due to they have the willing to retired and manage the current depsit in the bank.

part 5- Q & A
lijiangningzi@gmail.com
