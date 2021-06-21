# ## Overvirew of the analysis:

The purpose of this project is to pick a data set from Amazon product reviews. Pyspark was used to perform an ETL process by extracting the data, transforming the data and connecting to the database that was generated through the AWS webserver. The goal with the reviews is to try and determine if there is favorable review bias from the Vine members of our data set.

## Results
![](https://github.com/ahsaleh90/Amazon_Vine_Analysis/blob/main/img/vine_reviews.png)
There was a total of 1266 vine reviews for the toys dataset.

There was a total of 62028 non-vine reviews for the toys dataset.

There was a total of 432 five star reviews were vine.

There was a total of 29982 five star reviews were non-vine.

![](https://github.com/ahsaleh90/Amazon_Vine_Analysis/blob/main/img/non_vine_reviews.png)

The percentage for the vine five star reviews were 34.12%.

The percentage for the non-vine five star reviews were 48.33%.

## Summary
Looking at the percentage of the five star reviews for the vine and non-vine program shows that there is no positivety bias for the vine reviews. Since the percentage of the non-vine reviews is much larger than the percetage of the vine reviews.

## Further Analysis
Further analysis can be performed on the cusotmervotes where the ratio of the helpful votes can be reviewed while using verified purchase count.

