# Amazon Vine Analysis

## Purpose

We are analysing the potential bias of reviews that are paid for, versus reviews that are not paid for. To do this, we are using the PySpark library, and we perform a standard Extraction of the dataset, Transformation of the dataset, and Load the dataset to a database.

For this selection, we are analysing the data for Digital Video Games on Amazon. We get the total number of reviews, the total number of five star reviews, and the percentage of five star reviews for both paid and unpaid reviews.

## Results

### Unpaid Reviews

![Count of Total Reviews for Unpaid](https://i.imgur.com/Rwn90Yi.png)

As seen above, we have a total of 1,685 reviews for the Unpaid category.

![Count of Five Star Reviews for Unpaid](https://i.imgur.com/8Rwg80c.png)

We can see here that the number of five star reviews is 631.

![Percentage for Unpaid](https://i.imgur.com/haTKJQK.png)

And using those two numbers, we can get the percentage of five star reviews for the Unpaid Category.

### Paid Reviews

![No Data Available for Paid Reviews](https://i.imgur.com/qHcnSVi.png)

For paid reviews, there is no data available. There are no Paid Reviews in this category.

## Summary

The only summary to provide is that there is no data to present an actual case of bias towards Paid vs Unpaid, since this dataset does not contain any paid reviews. We cannot perform an analysis for our selected category with the goal we had in mind, and can only say that there is no bias present.

