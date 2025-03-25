# New York City Airbnb Project


## Project Overview

In this project we will gain valuable insights about the price of each room type (Hotel room, Entire home/apt, Shared room and Private room) in New York City. We will also explore the 5 boroughs Manhattan, Brooklyn, Queens, The Bronx, and Staten Island.


## Dataset Source

The dataset contains valuable information such as price, neighbourhood and room type. In the link that follows you will find more details about the data, including the meaning of each column and how the dataset was collected.

https://www.kaggle.com/datasets/vrindakallu/new-york-dataset/data
"New York Airbnb Open Data 2024"


## Data Cleaning

- Step 1: Handling missing values
- Step 2: Handling duplicates
- Step 3: Data types

We can see that column 'rating' has data type object. I decide not to change it because lot of rows had vaue 'No rating'.


## Exploratory Data Analysis (EDA)

Average price per night is around $188, but we can see that minimum is 10$ and maximum is $100000.

We can see that this dataset has outliers from the boxplot we create. That's why we focused on prices under $2000.

Notice the maximum number of beds in the dataset is 42.

The difference between the highest average price borough and the lowest is around 110$. As we can see Manhattan is on top ($227.95) and Brooklyn follows ($187.09). Queens, Staten Island and the Bronx are cheaper options with average price slightly higher tahn $110.  


## Some Results

![Image](https://github.com/user-attachments/assets/834d77d9-2fd1-48b7-a675-04ddf4f36d03)

With the help of Tableau we can see the map of NYC with all 5 boroughs and the average price. 
<img width="491" alt="Image" src="https://github.com/user-attachments/assets/3a776b7a-2537-470c-8cce-983317bc4b9b" />
