
Zomato Indian Restraurants | A Case Study

Introduction

Zomato is an Indian restaurant search and discovery service founded in 2008 by Deepinder Goyal and Pankaj Chaddah. It currently operates in 23 countries, including Australia and United States. It provides information and reviews on restaurants, including images of menus where the restaurant does not have its own website.

Inspiration and Vision

I was always astonished by how each of the restaurants are able to keep up the pace inspite of that cutting edge competition. And what factors should be kept in mind if someone wants to open new restaurant. Does the demography of an area matters? Does location of a particular type of restaurant also depends on the people living in that area? Does the theme of the restaurant matters? Is a food chain category restaurant likely to have more customers than its counter part? Are any neighborhood similar ? If two neighborhood are similar does that mean these are related or particular group of people live in the neighborhood or these are the places to it? What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. There are infacts dozens of question in my mind. lets try to find out the answer with this dataset.

Dataset

We have developed and tested our system based on the dataset that has been collected from the Zomato API. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

• Restaurant Id: Unique id of every restaurant across delhi and cities of the world

• Restaurant Name: Name of the restaurant

• Country Code: Country in which restaurant is located

• Country Code: Country in which restaurant is located

• City: City in which restaurant is located

• Address: Address of the restaurant

• Locality: Location in the city

• Cuisines: Cuisines offered by the restaurant

• Average Cost for two: Cost for two people in different currencies

• Has Table booking: yes/no

• Has Online delivery: yes/ no

• Price range: range of price of food

• Aggregate Rating: Average rating out of 5

• Votes: Number of ratings casted by people

Questions Discussed

1. The dataset is highly skewed toward the cities included in Delhi-NCR. So, we will summarise all the other cities in Rest of India while those in New Delhi, Ghaziabad, Noida, Gurgaon, Faridabad to Delhi-NCR. Doing this would make our analysis turn toward Delhi-NCR v Rest of India

- Compare the number of restaurants present in Delhi NCR vs Rest of India.

-Find the cuisines which are not present in restaurant of Delhi NCR but present in rest of India.Check using Zomato API whether this cuisines are actually not served in restaurants of Delhi-NCR or just it due to incomplete dataset.

-Find the top 10 cuisines served by maximum number of restaurants in Delhi NCR and rest of India.

- Write a short detailed analysis of how cuisine served is different from Delhi NCR to Rest of India. Plot the suitable graph to explain your inference.

2. User Rating of a restaurant plays a crucial role in selecting a restaurant or ordering the food from the restaurant.

~ Write a short detail analysis of how the rating is affected by restaurant due following features: Plot a suitable graph to explain your inference.

- Number of Votes given Restaurant

- Restaurant serving more number of cuisines.

- Average Cost of Restaurant

-Restaurant serving some specific cuisines.

~ Find the weighted restaurant rating of each locality and find out the top 10 localities with more weighted restaurant rating?

-Weighted Restaurant Rating=Σ (number of votes * rating) / Σ (number of votes) .

3. Visualization

- Plot the bar graph top 15 restaurants have a maximum number of outlets.

- Plot the histogram of aggregate rating of restaurant( drop the unrated restaurant).

- Plot the bar graph top 10 restaurants in the data with the highest number of votes.

- Plot the pie graph of top 10 cuisines present in restaurants in the USA.

- Plot the bubble graph of a number of Restaurants present in the city of India and keeping the weighted restaurant rating of the city in a bubble.

Acknowledgements

The data scraped was entirely for educational purposes only. Note that I don’t claim any copyright for the data. All copyrights for the data is owned by Zomato Media Pvt. Ltd..

