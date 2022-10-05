# Cemmercial-Bank-Marketing-Campaign

## Agenda 
##### Part 1- Client Demographic
##### part 2- Results from the Last Campaign
##### part 3- Analysing 
##### Part 4- Discussion and Recommendation
##### part 5- Q & A




## Part 1- Client Demographic
##### The purpose of today's discussion is to share predicting insights of our potential client from the last campaign.
##### Before we dig into that, let's do a recap of the client demographic.
##### Focusing group on Variable - y - has the client subscribed to a term deposit? ("yes","no")


![1](https://user-images.githubusercontent.com/43142255/194160532-355449b4-09f0-4173-8408-bec7f070aa29.png)

## Part 2- Results from the Last Campaign
##### This is the outcome of the previous campaign 
##### With a total of 42600 people.
##### There are about 10% subscribed to our products (term deposit).
##### Since our discussion purpose is to look into the factors that encourage people to subscribe to our products.
##### For the rest of the discussion, we will be focusing on the 4200 subscribers.


![2](https://user-images.githubusercontent.com/43142255/194160563-8a93553a-6220-4eae-98f5-bda654590f22.png)




## Part 3- Analyzing

#####  part 3- Models On Python
##### We first checked on missing data and missing cells, missing values in the training dataset. Amount 17 variable, we focus on our target group, Y is the target variable While 'no' means the client did NOT subscribe to a term deposit While 'yes' means the client subscribed to a term deposit



![3](https://user-images.githubusercontent.com/43142255/194160577-b399ca92-ee68-4c8b-ae76-a98057c18e02.png)

![4](https://user-images.githubusercontent.com/43142255/194160587-e400a908-2a7b-44ad-b8b5-445e0ba863bd.png)


##### From the following analyzing result, it is clearly shown that
##### 1- Age range for subscribers are higher than non-subscribers. 
##### 2- Bank statement Balances of subscribers are higher than non-subscribers. 
##### 3- Subscribers contacts about 1-day fasters than non-subscribers. 
##### 4- The average duration of the last contact is 2.6 times higher in the subscription group.

##### Interestingly, on the other hand, the number of days that passed after the last contact with the client, from a previous campaign is smaller

##### 1- Average days of users who purchased financial products (days since last contacted the customer) 
##### 2- The campaign should be less than the average days of non-purchasing users, which is reasonable because the smaller the pdays 
##### 3- The closer the day of the last call, the stronger the user's memory of financial products, and therefore the greater the chance of sales. 
##### 4- If the average campaign of users who purchase financial products (the number of phone calls with users) 5- Similarly, the average campaign of users who have not purchased.


![5](https://user-images.githubusercontent.com/43142255/194160602-d19dc092-3fdb-4746-81f0-169091708679.png)

##### Relative to Job Variables for the conclusion:
##### 1- It is clear to see that the number of term deposits is varies by work. 
##### 2- Management is the top buyer, but the non-subscribers are ranking second. 
##### 3- Numbers in blue-collar, admin are relatively large.

![6](https://user-images.githubusercontent.com/43142255/194160611-11c78607-c6fb-406f-8fe3-2e0bbe69a84a.png)

##### Relative to Marital Stutas Variables 
##### 1- Marital status doesn't show strong relative to subscribers' preference. 
##### 2- Single/Divorced people are more likely to make a term deposit.

![7](https://user-images.githubusercontent.com/43142255/194160629-f9fea8a2-b361-4d40-8b5b-46a4afcb18b9.png)

##### During the holiday season, December, it is unlikely for people to make a term deposit.


![8](https://user-images.githubusercontent.com/43142255/194160642-676ae438-e172-41ae-9346-7bfcdeada65a.png)


## part 3- Models On R
##### 1- Using Random Forest Model for the machine learning algorithm.
##### 2- Combing the 17 variables decision trees.
##### 3- Evaluate the total trees for taking a majority vote.
##### 4- The greater the trees in the random Forest Model, the more actually the prediction will be.
##### Example Trees Shown below:

![9](https://user-images.githubusercontent.com/43142255/194160665-e4fa9ee3-69f8-4825-8c72-b1f1680a47a4.png)



## Part 4- Recomandation

![10](https://user-images.githubusercontent.com/43142255/194160678-3c653b16-3120-44c7-b5d7-d2a32ccb565b.png)

##### ***There is a certain opportunity for management and technician clients.
##### People have the potential willing to subscribe 
##### People who have cell phone contact number
 
![11](https://user-images.githubusercontent.com/43142255/194160681-dd395873-323c-4b30-863c-f68a91a0b408.jpg)

![11](https://user-images.githubusercontent.com/43142255/194160697-5b74aecd-d950-48d0-8a45-e97e7963e136.png)![12](https://user-images.githubusercontent.com/43142255/194160709-c1e13f6e-296c-4a42-aa2d-f71c2497ee18.png)

##### ***With bigger pictures in strategy
##### we are not only going to focus on the client who has a lot of balance in our current deposit account. 
##### People with low balances in the bank, but work in the management and technology industry might have more bank accounts than one.
##### For the business strategy, people who have less than 100 dollars in the bank account are actually in the management industry. 
##### This means people have high incomes that might have the possibility to own several bank accounts. 
##### We will try to contact people who have less balance in their bank account to transfer their term deposits from another bank to our bank. 



