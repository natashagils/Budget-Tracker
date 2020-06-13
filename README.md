# Budget Tracker

# Synopsis

This is an online/offline budget tracker. Users are able to add expenses and deposits to their budget with or without a connection. 


# User Story
* AS AN avid traveller
* I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
* SO THAT my account balance is accurate when I am traveling


# Screenshot 
<img width="925" alt="Screen Shot 2020-06-13 at 2 54 25 PM" src="https://user-images.githubusercontent.com/56641651/84576856-c7a5aa00-ad85-11ea-92b6-78b5ea1f6ec4.png">


# Acceptance Criteria 

GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.


# Sample Code


> let transactions = [];
> let myChart;

> fetch("/api/transaction")
 >  .then(response => response.json())
 >  .then(data => {
 >    // save db data on global variable
 >    transactions = data;
 >    populateTotal();
 >    populateTable();
>     populateChart();
>   });

  
  
 # Installation
To use this portfolio, log into your GitHub account (if you don’t have a GitHub user profile, create one at https://github.com/join) and open this link in your browser: https://github.com/natashagils/budget-tracker. Then click on the "Fork" button at the top right corner and wait until the repo is forked. 

 
