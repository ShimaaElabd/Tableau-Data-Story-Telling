# Create a Tableau Story For (Loan Data from Prosper)

By Shimaa Elabd

Date: January 13, 2019

In This project I've explored and visualized. the **Loan Data from Prosper** This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Here's The Linkes to My Tableau Story:
- [A Story about the "Prosper" Before Feedback](https://public.tableau.com/profile/shimaa6990#!/vizhome/AStoryabouttheProsper/Story1) 

- [A Story about the "Prosper" After Feedback](https://public.tableau.com/profile/shimaa6990#!/vizhome/AStoryabouttheProsper_2/Story12) 

## Table of Contents
- [Introduction about Prosper](#intro)
- [Part I - Summary](#Summary)
    - [Trends](#Trends)
    - [Insights](#Insights)    
- [Part II - Design](#Design)
- [Part III - Feedback](#Feedback)
- [Part IV - Dataset](#Dataset)



<a id='intro'></a>


<img width="639" alt="15bce55ae4d83412bf085346000935c073426921" src="https://user-images.githubusercontent.com/25883512/51700432-ca302400-2017-11e9-9166-62d96b3aaf59.png">

**Prosper** is a peer-to-peer lending platform that aims to connect people who need money with those people who have the money to invest and It's one of the pioneers marketplace, lending which connects good-credit borrowers with investors who can choose to fund their loans.

## Summary
<a id='Summary'></a>

<a id='Trends'></a>
### Online personal loans trends:

In my Tableau story firstly I wanted to know the trend of the personal loans whether it's increasing over years or decreasing.
So I have done exploration on the loans over years and I've found out that the online personal loans trend climbed up over time!

**The current loans from 2010 to 2014 climbed up from 270,800 to higher than 144 Million!**

### Lender's Yeild trends:

And ofcoure We also want to know the trend of Lender's Yeild whether it's increasing over years or decreasing.
So I have done exploration on the Lender's Yeild over years and I've found out that the Lender's Yeild  trend climbed up over years!

<a id='Insights'></a>

### Borrowers' Loan Amounts in Different States:

- Borrowers' Loan Amounts have obvious variance in Different States. For example, In Canada the loan original amount is higher than 132 Million But in Arkansas state the loan original amount is about 6 Million.

### Borrowers' Rates in Different States:

- Borrowers' Rates have obvious variance in Different States. For example, In Arkansas state the Borrowers' Rates is higher than 2 But in De Lawrr the Borrowers' Rates is about 1.7



### Relationship between The Estimated returns and losses.

I have done exploration on the relationship between The Estimated returns and estimated losses, And I found out that higher estimated returns comes up with higher estimated losses which means higher risks. 


<a id='Design'></a>
## Design:

**I've chose to use Line Chart becouse it Works well in showing trends chronologically and Visualize data changes at a glance As Known that line graphs work out best in representing experiment statistics and data changes over time**

- The Online personal loans trend climbed up over time. => `Line Chart`
    - And I choose to use different colors to stand for different Loan status.


- The Lender's Yeild  trend climbed up over years.      => `Line Chart`


- Borrowers' Loan Amounts have obvious variance in Different States.  => `Thematic Maps.`
    - And I choose to use filter of Loan status to the Visualize for each Loan status or all of them at once.
    - Use Loan original Amount as color filter to visualize the variance of the amount of loans.


- Borrowers' Rates have obvious variance in Different States.  => `Thematic Maps.`
    - And I choose to use filter of Loan status for the same reason above.
    - Use Loan original Amount as color filter for the same reason above.


- The Estimated returns and Estimated losses => `Bar Chart`.
    - with one bar for each ProsperRating and I chose to use the length of the bar not the color to show the difference in ranges of losses and returns within that ProsperRating loan.
   
<a id='Feedback'></a>
## Feedback:

- I shared my first tableau story on Udacity slack group and shared with my friends on Facebook.

- Openions:
    - Use colors rather than length in Bar charts. (But I think that using length not colors is less confusing for audiance so I keep this)
    - The sequence of the story is not very well arranged.
        (I Changed the story to be more arranged and easy to get to audiance so I divided to two parts: the trends in first to talk in general about the trends in Prosber data the start showing the insights I come up with)
    - The caption in the last slide of the story is not very explaining what's happening.
      (So I changed the caption to be more understandable for audiance)

    

<a id='Dataset'></a>
## Dataset:

- [Prosper Loan Data - From Udacity](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

- [Prosper Loan Data - VariableDefinitions](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)
