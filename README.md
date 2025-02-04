
# Amsterdam Airbnb Open Data Project

## Table of Contents
- [Introduction](#introduction)
- [Scope](#scope)
- [Datasets](#datasets)
- [Technologies](#technologies)
- [Outcome](#outcome)
- [Resources](#resources)

## Introduction
Airbnb has revolutionized the way people travel by offering a more unique, personalized experience. As part of the Airbnb Inside initiative, this dataset describes the listing activity in Amsterdam, North Holland, The Netherlands.

## Scope
By exploring this dataset, we aim to answer the following questions:
1. Does the room type affect the pricing?
2. How does the neighborhood impact the price of the listing?
3. What factors impact client reviews?

## Datasets
- `listings (Amsterdam, North Holland, The Netherlands).csv`

## Technologies
- Python 3.10.9

## Outcome
### Data Analysis Notes:
1. **License Issues**: 97 listings lack a valid license. This issue must be addressed promptly to avoid potential legal problems. A list of these listings can be extracted as a CSV file if needed.
2. **Missing Pricing Information**: 3790 listings were found without any pricing information. This significantly impacts data integrity and credibility for clients, as pricing is considered critical data. This list can be extracted as a CSV file.

### Answers to Our Questions:
1. **Does the room type affect the pricing?**
   - Our analysis shows that hotel listings tend to have the highest rate per night compared to other room types, indicating that room type does impact pricing.
2. **How does the neighborhood impact the price of a listing?**
   - The highest-priced neighborhood is De Pijp - Rivierenbuurt, rather than the most reviewed neighborhood. Based on this insight, we recommend revisiting the pricing strategy for listings in this neighborhood to better align with the market.
3. **What factors impact client reviews?**
   - Our analysis revealed that two main factors influence the number of reviews and overall traffic in a neighborhood: location and pricing. Listings with competitive pricing and a location near popular areas (such as Centrum-West) tend to attract higher traffic and generate more positive reviews.

## Resources
- The dataset was obtained from [Inside Airbnb](https://insideairbnb.com/get-the-data/)
