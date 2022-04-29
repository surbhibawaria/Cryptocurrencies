# Cryptocurrencies

## Overview

The popularity of bitcoin has caused a price jump that makes it unaffordable for many new investors. However, there are many many more cryptocurrencies available at more afordable prices.

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of the most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

### Purpose

The purpose of this analysis is to help Martha discover trends that will convince her firm to invest in these new currencies.

## Results

- Preprocessing the dataset in order to perform PCA

<img width="459" alt="Screen Shot 2022-04-28 at 5 47 13 PM" src="https://user-images.githubusercontent.com/95826875/166070241-74b2a025-ce48-4933-af75-82d92405f5bc.png">

- Reducing the dimensions of the X DataFrame to three principal components and placing these dimensions in a new DataFrame

<img width="281" alt="Screen Shot 2022-04-28 at 5 47 34 PM" src="https://user-images.githubusercontent.com/95826875/166070364-5f679cdf-59d7-4c6b-8b01-97e069d0c8a8.png">

- Creating an elbow curve using hvPlot to find the best value for K from the DataFrame.

<img width="833" alt="Screen Shot 2022-04-29 at 5 23 00 PM" src="https://user-images.githubusercontent.com/95826875/166071027-5adb56ba-50ca-4d61-b5b6-310c0be4ce82.png">


- Creating scatter plots with Plotly Express and hvplot to visualize the distinct groups that correspond to the three principal components

<img width="759" alt="Screen Shot 2022-04-28 at 5 50 20 PM" src="https://user-images.githubusercontent.com/95826875/166070059-16e1dd14-2dc7-4633-9357-fffb4dfd74d6.png">
