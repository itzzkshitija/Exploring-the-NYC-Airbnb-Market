<div id="badges">
  <a href="https://www.linkedin.com/in/kshitija-chilbule-b98515309/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

# Analyzing the Airbnb NYC Listings Market 🏨
[Download EDA File from here](https://github.com/itzzkshitija/Exploring-the-NYC-Airbnb-Market/blob/main/EDA.ipynb)
## Table of Contents
[Project Overview](#project-overview)
[Background](#background)
[Dataset](#dataset)
[Questions Addressed in the analysis](#questions-addressed-in-the-analysis)
[Key Insights](#key-insights)

## Project Overview 
In this project, we will conduct an in-depth exploratory data analysis on the Airbnb NYC 2019 dataset to uncover trends and patterns in rental listings. 

## Background 
Airbnb is an online marketplace connecting people who want to rent out their homes with people looking for accommodations in that locale. It currently covers more than 100,000 cities and 220 countries worldwide. For hosts, it's a way to earn money while protecting their property from potential damage. However, for guests, it's a risky venture that they should avoid.

For this project, we are analyzing Airbnb’s New York City(NYC) data for 2019. NYC is not only the most famous city in the world but also a top global destination for visitors drawn to its museums, entertainment, restaurants, and commerce. According to the Office of New York State Comptroller, NYC hosted 66.6 million visitors in 2019.

Data analysis on thousands of listings provided through Airbnb is a crucial factor for the company. Our main objective is to find out the key metrics influencing the listing of properties on the platform. For this, we will explore and visualize the dataset from Airbnb in NYC using basic exploratory data analysis (EDA) techniques. We have found out the distribution of every Airbnb listing based on their location, including their price range, room type, listing name, and other related factors. We have analyzed this dataset from different angles and developed interesting insights. This can help in making strategic data-driven decisions by the marketing team, finance team, and technical team of Airbnb.

## Dataset
[Download Dataset from here](https://github.com/itzzkshitija/Exploring-the-NYC-Airbnb-Market/blob/main/Airbnb.csv)
<ul>
<li><b>Id :</b> Unique for each Property Listing.</li>

<li><b>name:</b> Name of each Property Listing.</li>

<li><b>host_id:</b> Unique ID for a host who has listed the property on Airbnb.</li>

<li><b>host_name:</b> Name of host</li>

<li><b>neighbourhood_group: </b> Name of Each borough of NYC, Manhattan, Brooklyn, Queens, Bronx, State Island.</li>

<li><b>neighborhood: </b> Area in each borough of NYC</li>

<li><b>latitude, longitude: </b> Co-ordinates of each listed property</li>

<li><b>room_type: </b> Different types of rooms available for listing, Private room, Entire home/apt, Shared room.</li>

<li><b>price: </b> Price of listing.</li>

<li><b>minimum_nigths:</b> Mandatory number of nights to be booked for available for each type of property.</li>

<li><b>number_of_review: </b> Number of reviews for each Listed property</li>

<li><b>last_review: </b> Date on which last time the listing was reviewed</li>

<li><b>review_per_month:</b>  Number of reviews per month</li>

<li><b>calculated_host_listings_count:</b> Number of listings each host owns</li>

<li><b>availablity_365:</b> Number of days the given listing is available for booking</li>

</ul>

## Questions addressed in the analysis
<ul>
  ✅Which are the top 10 host IDs with the most listings?
  
  ✅Which are the unique neighborhoods in the dataset?
  
  ✅What are the top 10 neighborhoods with the most property listings?
  
  ✅What are the top 10 host names with the most listings?
  
  ✅Which are the unique neighborhood groups in the dataset?
  
  ✅What are the property listing counts for each neighborhood group?
  
  ✅Which neighborhoods belong to each neighborhood group?
  
  ✅What types of rooms are available in the dataset?
  
  ✅Which room type contributes to the highest number of listings in NYC?
  
  ✅What is the average price of all listings?
  
  ✅How many hosts have more than one listing?
  
  ✅Which neighborhood has the highest average price?
  
  ✅How many listings are available throughout the year?
  
  ✅What is the average minimum number of nights required for a stay?
  
  ✅How many listings have never been reviewed?
  
  ✅What is the average price for each neighborhood group, and which neighborhood group has the highest average price?
  
  ✅What is the average number of listings per host?
  
  ✅How many listings per neighborhood group by room type?
  
  ✅What are the top 10 most reviewed listings?
  
  ✅What is the average price for listings with less than 100 days of availability?
</ul>

## Key Insights

1. The Airbnb NYC 2019 dataset is considered to be a very rich dataset for exploring and uncovering trends and patterns in rental listings. The dataset contains 16 attributes and 48895 rows in total. We analyzed the dataset using Python and data visualization libraries and uncovered useful insights. 

2. Firstly we identified the top 10 hosts with the highest number of rental listings on Airbnb. The host with the host ID 219517861 is recorded with the highest number of property listings on Airbnb with a total of 327 listings.

3. It was seen that throughout the entire year, only 1295 listings were available. Data also reveals that the average number of listings per host is just 1 listing, suggesting that most hosts manage only a single property. 
 
4. Our dataset includes 221 unique neighborhoods, with Williamsburg standing out as the neighborhood with the most property listings, totaling 3,920 listings. It is followed by Bedford-Stuyvesant and Harlem, with 3,714 and 2,658 listings, respectively. Fort Wadsworth has the highest average price, at $800.

5. We analyzed the top 10 hosts to identify the one with the most property listings on Airbnb. Our findings show that Michael holds the top spot with 417 listings, making him the host with the highest number of properties. He is followed by David, who has the second-highest number of listings at 403. Additionally, our data reveals that 5,154 hosts have more than one listing on Airbnb.

6. The dataset includes five distinct neighborhood groups: Brooklyn, Manhattan, Queens, Staten Island, and the Bronx. It was found that Manhattan has the highest number of property listings on Airbnb, with a total of 21,661 listings, while Staten Island has the fewest property listings. The data shows that Manhattan has the highest average property prices, making it the most expensive area to live in NYC. In contrast, the Bronx has the lowest average property prices, making it the most affordable area in the city. Whereas Queens and Staten Island appear to have similar property prices.

7. The Airbnb NYC listings primarily consist of three room categories: Private room, Entire home/apt, and Shared room. Among these, the Entire home/apt has the highest number of listings, making it the most common room type, while the Shared room has the fewest listings. The average price for all listings is $152.72. 

8. On average, Airbnb listings in this dataset require a minimum stay of 7 nights. This indicates that, generally, hosts prefer longer bookings, possibly to reduce the frequency of turnover and related maintenance tasks.

9. According to the dataset, there are a total of 10,052 property listings on Airbnb that have not received a single review. This means that these listings have either not been booked by guests or, if they have been, no feedback has been provided by those who stayed. This lack of reviews could impact the visibility of these listings to potential guests, as reviews often play a significant role in helping users decide on accommodations.
