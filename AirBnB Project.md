# AirBnB Project

### Dashboard Link
https://public.tableau.com/app/profile/alexandru.manta/viz/AirBnBProject_16780304478020/Dashboard

## Project Usecase
An AirBnB host would like to expand the activity to increase revenue and would like to find out the profitable areas to buy the next accomodation.

### Kaggle Dataset Link:
https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset

Factors taken in consideration:

- Location
- Renting price and proitable seasons.
- Number of bedrooms and if that's a price factor

### Steps followed 

- Step 1 : Load data into Tableau Desktop, dataset is an .xlsx file.
- Step 2 : The sheets made by importing the files are "Calendar", "Listings". These will be linked through Inner Join.

<img width="598" alt="Screenshot 2024-06-16 at 12 39 04" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/f1b91f1c-b84f-4924-a253-3497784746ad">


- Step 3 : Creating an Workbook for vizualizations.
- Step 4 : The first Workbook created is Price per Zipcode where we are looking at the average price per area.

<img width="1298" alt="Price by Zipcode" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/be86a955-2338-4700-9cd6-afc32b360e18">


- Step 5 : Create a map for the previous Workbook which reflect the outcome for a better perspective of each area.

<img width="1299" alt="Price by Zipcode (map)" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/0596c914-4f16-4901-8998-4e4660c1834b">


- Step 6 : For the next Workbook we will look at when people are speding the most money on accomodation. To do that we will look at date and price variables. 

- Step 7 : We will use organize the date into weeks and the will sum up the price variable.

<img width="1298" alt="Revenue per year" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/9d6f32db-a1bc-4572-8799-3189eb7f7e48">


- Step 8 : Moving on to the next Workbook, we will consider the DISTINCT values on bedrooms variable to verify if there are outliers. Then we will convert to dimensions. Then next variable to add is the average price.

<img width="1298" alt="Bedrooms" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/cb87118f-ff9f-4a43-a2b7-a4cbc8ceedbe">

- Step 9 : For the last Workbook, we will consider the bedrooms (Count) and ID which need to be converted into value to be quantified.

<img width="457" alt="Count of bedrooms" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/7cc7e834-ce3b-4940-815f-0d145afe5053">

- Step 10: Dashboard creation and publishing to Tableau Public.

<img width="1294" alt="Dashboard" src="https://github.com/AlexandruMa11/TableauProjects/assets/113061506/7a4cebf6-b16e-4246-bcf3-1ff50eb8a1f3">
           
# Insights

A single page report was created on Tableau Desktop and it was then published to Tableau Public.

Following inferences can be drawn from the dashboard;

### [1] Price per Zipcode

   The most expensive Zipcode = 98134

   Average price per night = $206.6

   The cheapest Zipcode = 98125

   Average price per night = $64.7
           
### [2] Rent price and profit per season

    From the data analyzed we can see that there is not much activity from the beginning of January and all the way to March as usually people travel towards the end of the year, especially during winter holidays and during the summer for vacations, which could be seen reflected into the trend.
    The revenue for the month of December 2016 is double compared to the revenue from the month of January 2016.
  
  ### [3] Number of bedrooms and if that's a price factor
  
      The apartments with the most revenue recorded are the one with 1 bedroom followed by the ones with 2 bedrooms with half of the revenue. The apartments which bring the least revenue are the ones with 6 bedrooms.
      In terms of price per night, the number of bedroom is a significant factor as it is more bedrooms a house has, the pricier it gets.

      Average price per 1 bedroom: $96.2 
      Average price per 2 bedroom: $175.4
      Average price per 3 bedroom: $249.7
      Average price per 4 bedroom: $315.4
      Average price per 5 bedroom: $450.1
      Average price per 6 bedroom: $584.8
