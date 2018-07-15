# Credit Card Defaults

## Springboard, spring 2018 Capstone Project #1
## Brent Jensen

### Overview: 
The health of the credit card industry is best measured not by the number of customers, but rather by the number who pay their bills. High rates of defaults can cut into profits, or worse, can ruin a bank.
Banks want to keep accounts current. They seek to minimize risk of any kind, but most of all defaults on loans.
Delinquencies were low in 2017 compared to history, but will very likely rise again if the economy worsens.
#### The Client: 
If a bank could predict which clients were likely to default, they might avoid risk by: not extending additional credit, or by contacting at-risk clients to help or intervene.
But how can a bank know which clients will default? Are there any clues?
We can examine data and find correlations among clients, and predict likely clients who might default.
#### The Data: 
UC Irvine Machine Learning Repository has a file on credit card defaults from Taiwan in 2005. 
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients The set of 30,000 includes whether the account defaulted in the next month, as well as demographic and account data, including: gender, marital status, education attained, age, amount of household credit, and 6 month history of credit balance, payments, and defaults.

### CreditCardEDA 
a deep dive into the information.  histograms and statistics to get a visual idea of the data.  From the start, I knew I would wrangle the data and apply machine learning to predict default.  But along the way, there are insights to be found.  
For instance, I observed that credit amounts were rising fast.  I learned that payment history correlates most strongly with default, but other variables have slight correlation.  (Thus, I knew I could continue with my thesis that machine learning would give good results.)  

### Data Cleaning 
The data had gaps, outliers, and numerical data that could be changed to categorical.  This module contains all the preprocessing needed before machine learning.

### FeatureEngineering 
All the machine learning, and most of the tuning and feature engineering attempts I made along the way to achieve my results

### StatisticsCap1 
a different Springboard project involving statistic analysis.  It involves the same data set, so I put it into the same repository.  

### Story telling Springboard project 
another Springboard project where I tell a story.  Unrelated to my predictor, but it also uses the same data.

### Lower Risk, Fewer Losses
slides to my report
https://drive.google.com/file/d/1AwR7tqJAg_BDH1GJwEk0j2Rfz6x8VwCu/view?usp=sharing

### Loser Risk, Fewer Losses
my final report
https://drive.google.com/file/d/1R30fbRS_xLz42vgBwdMPjhDwYAY-9sfM/view?usp=sharing
