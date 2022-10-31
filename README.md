# GeoSpatial Data Project

## OBJECTIVE

The main objective of this project was to locate the new offices of a gaming company in the best place for the company to grow. The intention was to cover more or less all of the following worker requirements, as far as possible:

- Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design.
- 30% of the company staff have at least 1 child.
- Developers like to be near successful tech startups that have raised at least 1 Million dollars.
- Executives like Starbucks A LOT. Ensure there's a starbucks not too far.
- Account managers need to travel a lot.
- Everyone in the company is between 25 and 40, give them some place to go party.
- The CEO is vegan.
- If you want to make the maintenance guy happy, a basketball stadium must be around 10 Km.
- The office dog—"Dobby" needs a hairdresser every month. Ensure there's one not too far away.

## ANALYSIS

In order to carry out the analysis, the following steps were followed:

1. A database of startups worldwide has been consulted to choose a city to locate the company. After making several queries, it was found that San Francisco is in the top 3 cities with the following requirements:

- Greater number of companies that have raised at least 1 Million dollars. (1st place)
- Greater number of design companies. (3rd place)
- Greater number of gaming companies. (2nd place)

2. Using the same database, all the companies in San Francisco have been extracted through MongoDB to choose the best possible location within this city.

3. The Foursquare API have been used to obtain the closest exact latitude and longitude of the following locations:

- Outdoor park
- Starbucks
- International airport
- Night club
- Vegan restaurant
- Basketball stadium

5. Finally, the different distances have been weighted according to the importance of each one in order to obtain the ideal location (Five Prime Therapeutics offices):

- 16.7 km from San Francisco International Airport
- 39 m from Starbucks
- 2 km from Yerba Buena Gardens (Public park & ​​cultural space)
- 2.6 km from SFJAZZ (Club) & B-Side (Gastropub)
- 2.3 km from Gracias Madre (Organic & vegan Mexican cantina)
- 557 m from Chase Center (Golden State Warriors stadium)

## VISUALIZATION

In the following maps of San Francisco, it's possible to see where each of the locations is located:

<img src="/images/map_1.png">
<img src="/images/map_2.png">