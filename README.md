![image](https://github.com/user-attachments/assets/56c364d4-6fce-478f-ae6e-79c51204db77)

AIM:-
The project aims to predict the optimal price for a given cuisine and determine the best location to sell that cuisine with the help of scraped data from Zomato. provide insights into the restaurant scene in Bengaluru, India, by analyzing Zomato data: 

CONTEXT 📋:-
I was always fascinated by the food culture of Bengaluru. Restaurants from all over the world can be found here in Bengaluru, The number of restaurant are increasing day by day. Currently which stands at approximately 12,000 restaurants.
The dataset also contains reviews for each of the restaurant which will help in finding overall rating for the place.
These kind of analysis can be done using the data, by studying the factors such as
• Location of the restaurant
• Approx Price of food
• Theme based restaurant or not
• Which locality of that city serves that cuisines with maximum number of restaurants
• The needs of people who are striving to get the best cuisine of the neighborhood
• Is a particular neighborhood famous for its own kind of food.
The data was scraped from Zomato in two phase.After going through the structure of the website I found that for each neighborhood there are 6-7 category of restaurants viz.

METHODOLOGY  🛠️

PHASE I,

In Phase I of extraction only the URL,name and address of the restaurant were extracted which were visible on the front page.The URl's for each of the restaurants on the zomato were recorded in the csv file,
so that later the data can be extracted individually for each restaurant.This made the extraction process easier and reduced the extra load on my machine.

PHASE II,

In Phase II the recorded data for each restaurant and each category was read and data for each restaurant was scraped individually, 15 variables were scraped in this phase For each of the neighborhood and for each category their online_order,
book_table, rate, votes, phone, location, rest_type, dish_liked, cuisines, approx_cost(for two people), reviews_list, menu_item was extracted. See section 5 for more details about the variables.

SECTIONS 📚

✔️ Exploratory Data Analysis
✔️ Visualization
✔️ Rate Prediction
✔️ Restraurant Prediction
✔️ Recommendation System

CONCULSION:-
As per our analysis, if the person wants to open a remote kitchen in Bangalore he/she should prefer opening it in Shanti Nagar or Basavanagudi,since the place is having less no of restaurant which reduces the competition and it has some of the expensive restaurants in the Banglore, hence the person can deliver food at lower price which reduces the competition even further.
The second suggestion would be sell North Indian, South Indian cuisine as they are demanded the most by the customers and they can keep the price ranging from 300 - 400 Rs for Non vegetarian categoryand 200 - 300 Rs for vegetarian category.

CHALLENGES FACED:-
There are several limitations and challenges that arised during the project. Some potential challenges include:
Learning web scraping with different tools was challenging due to the diversity of tools, evolving website structures, anti-scraping measures, and the need for data cleaning and preprocessing.
Dynamic page scrolling posed an additional challenge during the data scraping process, requiring specific techniques and tools to effectively capture and extract the desired information from web pages that load content dynamically as the user scrolls.
Data quality and consistency were compromised in the scraped data from Zomato, with errors, missing values, and inconsistencies present, thereby impacting the integrity of the raw dataset.




