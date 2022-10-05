# Cemmercial BanK Marketing Campaign

Agenda
Part 1- Client Demigraphic
part 2- Results from Last Campaign 
part 3- Recommandation
Part 4- Discussion
part 5- Q & A


Part 1- Client Demigraphic
Thue purpose of today's discussion is to share predicting insights of our potential client from the last campaign
Before we dig into that, let's do a recap of client demigraphic

# client demigraphic
<img width="546" alt="Client Demegraphic" src="https://user-images.githubusercontent.com/43142255/194132794-8b4bcb77-9e53-4522-b81a-d60460fe7154.png">



<img width="261" alt="balance for 100 and management jobs" src="https://user-images.githubusercontent.com/43142255/194133357-b3d1f7df-a72a-4ca9-ab95-6cdb20b254b9.png">


Number of Instances: 42600 for bank.csv
Number of Variables: 17.
Variable information:

   # bank client data:
   1 - age (numeric)
   2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4 - education (categorical: "unknown","secondary","primary","tertiary")
   5 - default: has credit in default? (binary: "yes","no")
   6 - balance: average yearly balance, in euros (numeric) 
   7 - housing: has housing loan? (binary: "yes","no")
   8 - loan: has personal loan? (binary: "yes","no")

   # related with the last contact of the current campaign:
   9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
  10 - day: last contact day of the month (numeric)
  11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  12 - duration: last contact duration, in seconds (numeric)

   # other attributes:

  13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  15 - previous: number of contacts performed before this campaign and for this client (numeric)
  16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Marketing Campaign
  17 - y - has the client subscribed a term deposit? (binary: "yes","no")


# part 2- Results from Last Campaign 
# This is the outcomes from the previous campaign
# Whithin the total of 42600 people, there are about 10% subscribed to our products (term deposit)
# Since our discussion purpose is to look into the factors tthat encourage people to subscirbe to our products
# For the rest of the discussion, we will be focusing on the 4200 subscribers.


<img width="546" alt="Client Demegraphic" src="https://user-images.githubusercontent.com/43142255/194133504-f887a71d-d4d0-431e-9708-26e9972f75b4.png">
<img width="32" alt="Chart Descipe" src="https://user-images.githubusercontent.com/43142255/194133546-29095bb5-0db4-48e6-ad89-caa9622fe67a.png">



# part 3- Recommandation

# Models On Python
# We first checking on missing data and missing cells, missing values in train dataset.
# Amount 17 variable, we focus on our target group, Y is target variable
# While 'no' means clinet did NOT subscribed a term deposit
# While 'yes' means client subscribed a term deposit

![image](https://user-images.githubusercontent.com/43142255/194131622-4c85f959-8bbf-438b-a295-31915fbe4f6b.png)

<img width="384" alt="yes and no" src="https://user-images.githubusercontent.com/43142255/194134673-f6691dd7-1dd4-426b-a774-a040665af0a7.png">

# From the following analysing result, it is clear shown that

# 1- Age range for subscribers are higher than non-subscribers.
# 2- Bank statement Balance of subscribers are higher than non-subscribers.
# 3- Subscribers contacts about 1 day fasters than non-subscribers.
# 4- The average durations of last contact are 2.6 times higher in subscrition group.
# Interestingly, on the otherhand,
# number of days that passed by after the last contacted the client 
# from a previous campaign is smaller


# 1- Average pdays of users who purchased financial products (days since last contacted the customer)
# 2- Campaign should be less than the average pdays of non-purchasing users, which is reasonable because the smaller the pdays
# 3- The closer the day of the last call, the stronger the user's memory of financial products, and therefore the greater the chance of sales.
# 4- If the average campaign of users who purchase financial products (the number of phone calls with users) 
# 5- Similarly, the average campaign of users who have not purchased.

![image](https://user-images.githubusercontent.com/43142255/194134900-b91590ec-e81a-4bb0-92e8-36c8a51f3d5e.png)

# It is clear to see that the number of term deposit is various by works.
# Management is the top buyers, but the non-subscribers are ranking as second.
# *****Meanwhile there is a huge oppotunities in management and technician.
# Numbers in blue-collar, admin are relatively large.

![image](https://user-images.githubusercontent.com/43142255/194135043-ff047dd4-8328-4174-95e7-8e180315472f.png)

# Marital status doesn't show strong relative for subsribers' preference.
# Single/Divorced people are more likely make a term deposit.

![image](https://user-images.githubusercontent.com/43142255/194135248-536c10b9-21e4-4c72-9348-97f7b97c7f4b.png)


# On holiday season, December, it is unlikely for people to make a term deposit.

![image](https://user-images.githubusercontent.com/43142255/194135313-eeaf2d85-a1c0-463d-89ce-5f2c71e26eb9.png)






# Models On R
# Table 1
![image](https://user-images.githubusercontent.com/43142255/193896098-14b95c4e-8689-4bd0-81b5-4b508922f557.png)

# *****Meanwhile there is a huge oppotunities in management and technician.


# Table 2

![image](https://user-images.githubusercontent.com/43142255/193896658-9f0ff306-ddb5-47d2-991f-6f54d1070031.png)

# Table 3

![image](https://user-images.githubusercontent.com/43142255/193974536-1b7c3a21-43a4-4357-ab0c-e7ee52f0be25.png)


# Part 4- Discussion
<img width="98" alt="Balane Group With Credit" src="https://user-images.githubusercontent.com/43142255/194133392-33d50028-fe5f-4962-9b4b-e26cfcb6797c.png"><img width="100" alt="balance for 100 and management jobs - jobs categories" src="https://user-images.githubusercontent.com/43142255/194133433-1ba58ea0-3046-4318-9388-384c26caeed4.png">

# For the business strategy, people who has less than 100 dollor in the bank account is arctually in management industry.
# Which means, people has high income that might has the possibility to own several bank account.
# We will try to contact with people who has less balance in the bank account to transfer their term deposit from other bank to our bank.
# we are not only going to focust on the client who has a lot of balance in our current deposit account.
# People who age between 20-30 and singel is one target group, due to they don't have family pressure.
# People who age above 50 and divorce is another target group, due to they have the willing to retired and manage the current depsit in the bank.

# part 5- Q & A
# lijiangningzi@gmail.com
