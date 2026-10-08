# Airbnb Revenue Analysis (Tableau)

If you were buying a property in Seattle to rent out on Airbnb, where should it be and how big should it be? This Tableau analysis looks at Airbnb listings in Seattle to find what drives rental prices and revenue, and presents the answers in a dashboard aimed at property investors.

## Dashboard
[![Airbnb revenue Tableau dashboard](images/airbnb-dashboard.jpg)](https://public.tableau.com/app/profile/abir.hossain4647/viz/AirbnbRevenueAnalysis_17080290158200/Dashboard1)

**[View the interactive dashboard on Tableau Public →](https://public.tableau.com/app/profile/abir.hossain4647/viz/AirbnbRevenueAnalysis_17080290158200/Dashboard1)**

The dashboard shows average price by zip code (as a map and a bar chart), average price by number of bedrooms, and total revenue week by week through 2016.

## Key findings
- **Price grows steadily with size:** a 1-bedroom listing averages about $96 a night, a 3-bedroom about $250 and a 6-bedroom about $585.
- **Location matters:** average prices differ a lot between zip codes, from about $60 to over $200. Zip code 98134 has the highest average.
- **Revenue grew through the year:** weekly revenue rose from about 1.2M in early January to over 2M by the end of 2016, with no big seasonal dip.

## Data
Seattle Airbnb data for 2016: a listings table (property details such as zip code and number of bedrooms) and a calendar table (price per listing per day).

## What I did
- Profiled the data in Tableau to see what each table contains and where values are missing
- Joined the listings and calendar tables with an inner join
- Built calculations and aggregations, such as average price by bedroom count and zip code, and revenue by week
- Combined the visuals into an interactive dashboard designed for investors

## Files
| File | Description |
|---|---|
| `Link` | Link to the dashboard on Tableau Public |
| `images/` | Dashboard screenshot |

## Tools
Tableau
