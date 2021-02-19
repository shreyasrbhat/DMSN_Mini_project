## NETWORK ANALYSIS OF BITCOIN TRANSACTIONS

**Project title**: Identifying trusted and fraudulent users in the Bitcoin transaction network

### Discription
This project aims to model fraudulent transactions by analysing Bitcoin transaction trust network.

### About the data
The data is  records of network of users who carries out Bitcoin transaction in public. The user data is anonymous and each transaction is labelled between -10 to +10 in steps of one along with the timestamp of trascation.

So the basic structure of network is **signed directed graph**  
**Total users: 5881**  
**Total transactions: 35529**

```mermaid
A((user1))--Rating,Time-->B((user2))
```

### To be clarrified
- Is it a multi directed graph?
- can we use different dataset other than one in the description
- The concepts of social network may not apply here.

### in depth analysis
- How does average rating evolve over time
- What is the frequency of transcations carried out by users with good rating and bad rating
- Based on the rating and other network parameters can we model users rating in upcoming transaction.
- How communities evolve around trusted and risky users. (Triadic closure may not apply here as in social network)
