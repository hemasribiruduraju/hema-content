CONTEXT:-
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
PHASE I,
In Phase I of extraction only the URL,name and address of the restaurant were extracted which were visible on the front page.The URl's for each of the restaurants on the zomato were recorded in the csv file,
so that later the data can be extracted individually for each restaurant.This made the extraction process easier and reduced the extra load on my machine.
PHASE II,
In Phase II the recorded data for each restaurant and each category was read and data for each restaurant was scraped individually, 15 variables were scraped in this phase For each of the neighborhood and for each category their online_order,
book_table, rate, votes, phone, location, rest_type, dish_liked, cuisines, approx_cost(for two people), reviews_list, menu_item was extracted. See section 5 for more details about the variables.




