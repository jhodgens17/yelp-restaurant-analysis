# Reviewing Yelp data to inform decision on opening a restaurant in Long Beach Island, NJ

The purpose of this project was to use exploratory data analysis to generate insights around opening a business. This particular exercise was focused on opening a restaurant in the Long Beach Island area of the Jersey Shore. Data obtained from Yelp's API was leveraged to conduct the analysis. The specific goal of this project was to answer two questions - 1) Where specifically in the LBI region should the restaurant be located? and 2) What type of restaurant should it be (i.e. what category of cuisine)?

## Summary of data analyzed
Yelp data was pulled and reviewed for existing restaurants in the LBI region including:
- Ratings of each restaurant
- Total number of reviews
- Restaurant categories
- Locations (latitude, longitude, address, etc.)

## Key finding

Based on the anlaysis conducted in this exercise, there is an opportunity to open a sushi restaurant in the mainland region west of Long Beach Island or on the southern part of the island - or a burger restaurant on the mainland.

## Summary of the analysis
Data was pulled using the Yelp API for business information.
Two-hundred restaurants in the LBI region were reviewed as part of this exercise:
- 67 were located on the mainland area west of LBI
- 65 were located on the northern part of LBI
- 68 were located on the southern part of LBI


These restaurants were classified based on 70 categories including:
1. Seafood
2. Breakfast & Brunch
3. Sandwiches
4. American (Traditional)
5. Pizza
6. American (New)
7. Italian
8. Delis
9. Mexican
10. Burgers

Note: The above restaurant categories were the 10 most common in the dataset, but the top 23 were considered as options for the new restaurant.

## Deeper dive into the process/results*
- Less common restaurant categories (those with less than 5 restaurants in the LBI region) were filtered out from analysis
- The average number of reviews for each restaurant category was compared against the average rating (out of 5 stars) using a scatter plot
- Based on the scatter plot, the most popular categories of restaurants in LBI are Burgers, Sushi Bars, Seafood, American (New), American (Traditional), and Breakfast & Brunch
- The counts of restaurants for the six popular categories were plotted on a stacked bar chart for each area of LBI (mainland, island-north, and island-south) 
- In order to identify areas where a new restaurant would face strong competition, only restaurants with a rating greater than 3.5 were counted on the bar chart
- According to the bar chart, there are currently no highly rated sushi or seafood restaurants on the mainland and there are no highly rated sushi restaurants on the southern part of the island - this presents an opportunity for a new venture in LBI

*see Juptyer Notebook or presentation for data visualizations

## Repository Contents

Below is a list of the contents of this repository.

- `README.md`: The README for this repo branch explaining it's contents - you're reading it now
- `Hodgens Yelp Project.ipynb`: Jupyter Notebook containing complete analysis
- `Yelp Restaurant Review.pdf`: Slide deck providing an overview of the project
- `Additional files used for analysis` folder: A folder for all Jupyter notebooks and csv files used
- `Yelp_businesses.csv`: Restaurant dataset 

