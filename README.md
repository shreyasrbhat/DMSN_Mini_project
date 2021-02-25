## NETWORK ANALYSIS OF BITCOIN TRANSACTIONS

**Project title**: Identifying trusted and fraudulent users in the Bitcoin transaction network

### Discription
This project aims to model fraudulent transactions by analysing Bitcoin transaction trust network.

### About the data
The data is  records of network of users who carries out Bitcoin transaction in public. The user data is anonymous and each transaction is labelled between -10 to +10 in steps of one along with the timestamp of transaction.


### Baisc network analysis
So the basic structure of network is **signed directed graph**  
**Total users: 5881**  
**Total transactions: 35592**
#### out Degree distribution
**80 percent of users have rated less than 5 users**
**20 percent of users consitute 80 percent of ratings**
**18 percent of users never rated any other users**

#### Rating distribution
**Half of the rating are less than or equal to 1**
**Less than 10 percent of ratings are greater than equal to 4**

### Components
About 80 percent of users are part of strongly connected component 



### in depth analysis (WIP)
- How does average rating evolve over time
- What is the frequency of transactions carried out by users with good rating and bad rating
- Based on the rating and other network parameters can we model users rating in upcoming transaction.
- How communities evolve around trusted and risky users. (Triadic closure may not apply here as in social network)
