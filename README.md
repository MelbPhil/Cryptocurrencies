# Cryptocurrencies

Using an unsupervised machine learning algorithm to group cryptocurrency coins into different clusters.

## Overview of Cryptocurrencies

Here, I was tasked with creating a report taht determines how to group the cryptocurrencies that are currently trading in the market, such that new coins can be easily classified for easier investment strategising. I was provided with raw data, and needed to process the data to fit the machine learning model. After properly fitting this data to the unsupervised ML model, I then use some data visualization techniques to share my findings with the client.

## Results

After cleaning and scalling the data, I ended up with 533 coins that were actively being traded.

![Crypto_Table](https://user-images.githubusercontent.com/106599446/192117833-cf2001a3-6889-43fb-baae-cb2e4d95f09b.png)

These coins were clustered into 4 distinct classes:

![3D_Scatter](https://user-images.githubusercontent.com/106599446/192117889-8d90e2d5-07c9-4805-a65e-3b3f1e2fb43b.png)

Here you can visualize how the coins are desributed on a 2D scatter plot, where the x-axis is 'TotalCoinsMined' and the y-axis is 'TotalCoinSupply'

![2D_Scatter](https://user-images.githubusercontent.com/106599446/192117900-5c62e8a4-25a7-43dc-bba9-4fedc32aae38.png)

## Summary

The 2D plot makes it rather difficult to visualize why these coins require 4 groups; this is much more apparent when visualizing the coins in the 3D scatter plot. Perhaps adding some more metrics for the Crypto Currencies would help better differenciate between the coins, as the majority of the coins are all currently being clustered in the same groups.
