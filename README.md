✈️ Airlines Flights Data Analysis
🚀 Discover Indian flight trends, ticket prices, and booking insights — all in one interactive notebook!

📂 Project Highlights
🧹 Data Cleaning: Remove nulls, trim text, fix formats!

🔍 Exploration: Analyze airlines, routes, timings, classes, prices — everything!

📊 Visualizations:  graphs — by airline, route, price, and more!

💡 Business Insights: Which route is cheapest? Is last-minute booking always expensive? Find out here!

🗂️ Dataset Details
# Flight Data

| ✈️ Column        | 🔎 Description                                 |
|------------------|------------------------------------------------|
| airline          | Airline name                                   |
| flight           | Flight number/code                              |
| sourcecity       | Departure city                                  |
| departuretime    | Departure time slot (Morning, Evening, etc.)    |
| stops            | Number of stops (zero, one, etc.)               |
| arrivaltime      | Arrival time slot                                |
| destinationcity  | Arrival city                                     |
| class            | Ticket class (Economy/Business)                  |
| duration         | Total flight duration (hours)                    |
| daysleft         | Days left to departure                           |
| price            | Ticket price (INR)                               |

## Example rows

| airline     | flight   | sourcecity | departuretime | stops | arrivaltime | destinationcity | class   | duration | daysleft | price (INR) |
|-------------|----------|------------|----------------|-------|-------------|------------------|---------|----------:|---------:|------------:|
| Indigo      | 6E-1234  | Delhi      | Morning        | zero  | Midday      | Mumbai           | Economy |       2.0 |        5 |      4500   |
| Air India   | AI-567   | Mumbai     | Evening        | one   | Night       | London           | Business|      10.5 |       30 |    65000    |


📒 Open the notebook:

text
jupyter notebook airlines_flights_data.ipynb
🗃️ Ensure flightsdata.csv is in the project folder.

🚦 Interactive Visuals
🎨 What you will visualize:

🏆 Top airlines by ticket sales!

📈 Booking trends (Days left vs. Price)

🏙️ Source and destination route analysis!

🛫 Price comparison by airline and class!

