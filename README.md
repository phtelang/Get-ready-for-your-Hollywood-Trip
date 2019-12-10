## Get ready for your Hollywood Trip
In this project, I scraped Los Angeles hotel data from 20 pages from the TripAdvisor website. I used BeautifulSoup python package which creates a parse tree from parsed HTML and XML documents. After collecting the data, I analyzed the prices, ratings and reviews and used VaderSentiment to assign sentiments to hotel reviews. 
We will look at different features like price, discounts, amenities and rating which will help you book a hotel the next time you plan a trip to LA! We will also analyze the reviews to understand that the next time you book a hotel and pay a higher price for a high rated hotel, is it actually worth it?

For this, we will:
1. Analyze relationship between hotel price and rating, discount and rating, discount and price, rating-wise average hotel price.
2. Explore popular hotel amenities.
3. Rating-wise hotels with maximum price, rating-wise hotels with minimum price, rating-wise hotels with maximum discount.
4. Hotels with maximum discounts, top hotel booking providers.
5. Analyze hotel reviews to find top 20 frequently occuring words.
6. Assign sentiment to hotel reviews and analyze them.
7. Analyze whether high rated hotels are worth the money based on the reviews.

### Summary of Results
1. There is a general trend of rating increasing as the price increases. But you can see many hotels with rating more than 4 also having a lower price indicating that hotels with good service, amenities and/or discounts are rated high.
2. Free wifi and free parking are the most popular amenities offered by hotels in LA.
3. 4.5 rated hotels have the highest average price, but you can find a good hotel at rating 4.0 and 5.0 for a lower cost!
4. We can see that as the rating increases, more and more discounts are offered except for the rating of 5.0. Majority of the hotels are not offering any major discounts, but we can see a slight trend that as the price increases, the discounts also increase. Most of the discounts are less than $50.
5. Booking.com is the most popular site for hotel bookings and discounts.
6. Maximum hotels with rating 3.0 have a high number of reviews with positive sentiment. Hotels with rating less than 1.5 have more negative sentiments. So, we can conclude that slightly higher price for a good hotel rated above 3 also is worth it!

To view the code and graphs accurately, please __[click on this link](https://nbviewer.jupyter.org/github/phtelang/Get-ready-for-your-Hollywood-Trip/blob/master/Get%20ready%20for%20your%20Hollywood%20Trip%21.ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the .ipynb (Jupyter file).
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.) 
