Project Title
 Amsterdam Airbnb Open Data Project
Table of contents
•	Introduction
•	Scope
•	Datasets
•	Technologies
•	Outcome
•	Resources
Introduction
Airbnb has revolutionized the way people travel by offering a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of (Amsterdam, North Holland, The Netherlands)
Scope
By exploring this dataset, we will be looking for answers for the below 3 questions:
1- Does the room type affect the pricing?
2- Who the neighborhood impacts the price of the listing?
2- What factors impact clients reviews?
Datasets
listings (Amsterdam, North Holland, The Netherlands).csv
Technologies
This project uses Python 3.10.9 version
Outcome
Notes of our data analysis:
1- During data wrangling, we found that 97 listings lack a valid license. This issue must be addressed promptly to avoid potential legal issues & list of these listings can be extracted as CSV file if needed.
2- A list of 3790 listings was found without any pricing information This significantly impacts data integrity and credibility for clients, as pricing is considered critical data. This list can be extracted as a CSV file.

After exploring the datasets, here are the answers to our questions:

1-Does the room type affect the pricing?
Our analysis shows that hotel listings tend to have the highest rate per night compared to other room types, indicating that room type does impact pricing.
2-How does the neighborhood impact the price of a listing?
In our analysis, we found that the highest-priced neighborhood is De Pijp - Rivierenbuurt, rather than the most reviewed neighborhood. Based on this insight, we recommend revisiting the pricing strategy for listings in this neighborhood to better align with the market.
3-What factors impact client reviews?
Our analysis revealed that two main factors influence the number of reviews and overall traffic in a neighborhood: location and pricing. Listings with competitive pricing and a location near popular areas (such as Centrum-West) tend to attract higher traffic and generate more positive reviews.

Resources
The dataset was obtained from link https://insideairbnb.com/get-the-data/
