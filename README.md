# Airbnb Price Prediction
### Introduction
Airbnb was started in 2008 by Brian Chesky and Joe Gebbia, and since then, it has gained popularity due to its low prices and direct interactions with the local community. Airbnb is an online home-sharing platform where people can list or rent properties for short-term use. Be it a spare bedroom, an apartment, a villa, a private island, or even a sofa, anyone looking to earn some profit can promote their space on Airbnb.

Airbnb provides its guests with many options and varieties such as the types of apartments, types of rentals, etc. but not a lot of functionality is provided to the hosts/homeowners to determine the optimum price for their listings. Airbnb listing price is a significant factor that hosts must get right. Especially in big cities like Amsterdam, where there is a lot of competition, even the slightest variations in the prices can get the listing priced out of the market. While listing out a property, Airbnb suggests a base price by considering property details, locations, and similar properties in the area. Some third-party services and websites provide general guidance, but none of them are free. Since the holiday letting market is constantly changing, hosts should be diligent in monitoring and adjusting their prices instead of only focusing on the base price initially set by Airbnb.

In this project, we think from the homeowner's perspective and try to determine the various factors that impact the listing prices most. By doing this, we help the hosts determine the optimum nightly price for their listings and maximize their earnings from the listings. We decided to work on the Airbnb data of one of the biggest cities, Amsterdam. Unlike other cities, Airbnb has not been in a favorable position in Amsterdam due to newly established renting regulations and close competition with apartments and other rental services. We will analyze multiple data sets collected from insideAirbnb, including parameters like availability, neighbors, room types, fees, and more. In addition, we will explore the guest reviews and impact of the reviews on Airbnb rentals to help hosts make better decisions.

### __Questions of Interest__


● __How does the accessibility to various amenities affect the price of Airbnb listings?__

● __What are the various factors which affect the reviews? What insights can we gain from them?__

● __Which areas have the most Airbnb properties, and which are the most expensive?__

● __How can we help Airbnb hosts to determine the optimum nightly price for their listings?__

● __What are the various factors which affect the Airbnb listing?__


### Data Aquisition
The datasets used for this project were collected from the website [Inside Airbnb](http://insideairbnb.com/), which is an independent, non-commercial, open source data tool. This investigatory website scrapes and reports publicly available information about a city's airbnb listings. The dataset used in this project was scraped on September 7th, 2021 and it contains information on all Amsterdam listings which were live on the website on that day. 

We have used the following datasets from the website:

- `listings` : This dataset contains a record for every listing published on the website for the city of Amsterdam. It contains important information such as listing neighbourhoods, property type, room time, amenities, price etc along with all the host information. This dataset has a total of 16117 rows and 74 columns. We mostly focus on this particular dataset since it has very detailed information of a particular listing that can be analyzed to make inferences. 

- `reviews` : This dataset contains information regarding guests and the reviews they have published on the website for the listings they have rented out. It has a total of 16117 rows and 6 columns. We also have review rating information of listings in the 'listing' dataset, for example average rating ,rating based on cleanliness, rating based on communication etc. We will use both of these dataset to analyze the impact of ratings. 

- `calendar` : This dataset contains information regarding the price and availibility of the listings published on the website. It has a total of 1048576 rows and 7 columns.


Even though the compiled data provides useful basis for examining and monitoring Airbnb practices, it has some critical limitations. The major one is that it only includes the advertised price. The sticker price is the overall nightly price that is advertised to potential guests, rather than the actual average amount paid per night by previous guests. The advertised prices can be set to any arbitrary amount by the host, and hosts that are less experienced with Airbnb will often set these to very low or very high.

### Setting Up
To set up this project, you will require the following tools:

Anaconda
1. Jupyter Lab
2. Python 3.0.0+
3. Please make sure that you have installed all the libraries used in this project.

Once you are done setting up the environment, You can run the Jupyter Notebook on Anaconda. Make sure to change the path of the data as per your convinience. You can also check out the presentation report or the HTML report in order to avoid running the Jupyter Notebook.

### Final Thoughts
This project can be used by any home-sharing platform to predict the optimum nightly prices for their listings.
