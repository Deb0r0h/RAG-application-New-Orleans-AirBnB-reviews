# NLP Project: New Orleans Air BnB reviews RAG application

The code inside the notebook allows you to talk to the system and get information, opinions and recommendations regarding BnBs in the city of New Orleans based on customer reviews on the AirBnb platform

Ex:
- Question: Which apartment is near restaurants?
- Answer: Based on the reviews provided, multiple apartments have been mentioned for having easy access to restaurants. These include "New Orleans Uptown Tall Tales" with ID 11675374, "Boutique Artful & Sun-Bathed Uptown Studio" with ID 45701740, "Valence Victorian:Walk to Tulane, Cafés & Eateries" with ID 38489419, "Uptown Trendy Neighborhd Apt permit# 17STR-06483" with ID 4966135, "Artists/Yogi RetreAt in NOLA!" with ID 27488144, and "Bright, Beautiful Apartment in Excellent Uptown Location" with ID 23230947. All these apartments have received positive feedback regarding their proximity to various dining options.

- Question: Which host turned out to be the most popular and why?
- Answer: Based on the reviews provided, Ernest (host ID: 210139707), who manages the listing "The Esprit Mini Loft: Tulane/Loyola/Freret," stands out as the most popular host among those listed. This conclusion is drawn from the fact that he received multiple positive reviews mentioning him as a great host who was very responsive and helpful, providing excellent local recommendations. For instance, in two separate reviews, guests mentioned that Ernest went above and beyond by sharing valuable information about restaurants and happy hours in the area. These personal touches and attentiveness seem to have left a lasting impression on the guests, making Ernest a highly regarded host.

We chose [this dataset](https://www.kaggle.com/datasets/ruthgn/new-orleans-airbnb-listings-and-reviews?select=new_orleans_airbnb_listings.csv) about AirBnB reviews in New Orleans. The dataset gathers together 345953 reviews of 6028 listings in the 67 districts of New Orleans.
For the purposes of this project we focused on the Uptown district, which has 6087 reviews over 98 listings.

The project was developed with the collaboration of [Andrea Segala](https://github.com/andreasegala)
