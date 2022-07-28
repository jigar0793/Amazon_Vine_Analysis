# Amazon_Vine_Analysis

## Overview

Our main objective is to pull, clean, and analyze data from Amazon video game reviews with the purpose of haveing a better understanding of Amazon Vine user activity. We will do this analysis on Google Colab with the help of the PySpark library. Our concern is to determine any possibility of biases towards reviews based on Amazon Vine customer status (Member vs Non-member)

## Results
Using PySpark in google Colab, we were able to filter the data to determine:

* The toal number of reviews (40565)
    * Reviews made by Vine Members (94)
        * 51.1% of reviews that are 5 Star reviews (48)

* Reviews made by Non Vine Members (40471)
    * 38.7% of reviews that are 5 Star reviews (15663)

## Summary

In conclusion, we can see that there is a difference in activity between members and non-members. Members are more likely to provide positive reviews (51.1%) compared to non-members (38.7%). This may indicate that there is some bias but there may be other outside factors at play. Another concern is the massive discrepency in sample size between the two cases. Another form of analysis that can be made is to do maybe find other factors and see how much they weigh in the decision of a positve or negative review