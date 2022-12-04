# Netflix Index

## Netflix
Netflix is the most popular streaming service in the world, being available in over 190 different countries. However, the price of Netflix is not the same among all of these different countries. Rather, they are adjusted to reflect the purchasing power of the local currency. Therefore, comparing the price of a standard monthly Netflix subscription will allow us to gauge the purchasing power parity of different currencies.

## How the Index was Created
### 1. Importing Data on Netflix
[comparitech.com](https://www.comparitech.com/blog/vpn-privacy/countries-netflix-cost/) provides a dataset containing the price of Netflix subscriptions for 88 different countries. Accessing the data was as easy as downloading a CSV file and selecting the desired information.

## 2. Cleaning the Data
Luckily, the CSV file was already very clean. There were no missing values, no incorrect data types, nor any misentered values. However, the dataset used an ampersand(&) in country names such as 'Bosnia & Herzegovina'. However, the API's I will be using use the actual word 'and'. This easy change was the only cleaning that needed to be preformed on the data.

##

