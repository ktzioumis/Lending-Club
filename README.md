# Lending-Club

## An exploration of Lending Club's loan data from 2007-2018 


### The Cold Foot Investor

This repo contains the companion notebook (https://github.com/ktzioumis/Lending-Club/blob/master/Cold-Foot-Investor.ipynb) to this blog post: https://medium.com/analytics-vidhya/the-cold-foot-investor-82da6c0baff0

Loan data provided by LendingClub.com on their loan returns from 2007 to 2018 including current and past loans. The dataset was obtained form Kaggle.com here https://www.kaggle.com/wendykan/lending-club-loan-data

The full dataset is reduced to subset of "completed" loans that have been either Fully Paid or Charged Off. The investor perspective outcomes for all these loans are are visualised in a boxplot broken down by grade and term:

<img src='/images/profit_grade_box.png'>

A conservative investment scenario is simulated with all loans from the year 2013 with an investment starategy of selecting 1000 loans graded either A or B and loan term of 36 months. The simulation is run 1000 times and provides a normally distributed return with mean 10.1% and standard deviation of 0.5

<img src = '/images/return_mc_hist.png'>

Note: investment return is over the loan **lifetime** not an annual return.
