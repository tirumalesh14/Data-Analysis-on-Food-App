README – Food App Data Exploration & Analysis (SQL Server)
📌 Project Overview
This project focuses on exploring and analyzing a Food Delivery App dataset using SQL Server.
The dataset contains 9000+ restaurant records with details such as Restaurant_ID, Restaurant_Name, City, Location, Cuisines, and more.

The main objective is to:

Understand restaurant distribution across countries and cities.

Analyze ratings, votes, cuisines, and service offerings.

Identify trends and insights for strategic decision-making.

🛠 Technologies Used
SQL Server

Windows Functions

Joins, Aggregations, and Filtering

Data Cleaning and Transformation Techniques

🔍 Data Exploration Tasks
Checked table details – column names, data types, and constraints.

Duplicate detection – identified and removed duplicates in Restaurant_ID.

Column optimization – removed irrelevant/unwanted columns.

Table merging – joined two tables and added a new Country_Name column using CountryCode as the primary key.

Data cleaning – corrected misspelled city names.

Rolling/Moving Counts – calculated number of restaurants over time using window functions.

Statistical Analysis – computed MIN, MAX, and AVG for Votes, Ratings, and Currency.

New features – created a rating category column for better segmentation.

📊 Key Insights from Analysis
Country-wise distribution:

90.67% of listed restaurants are from India.

USA comes next with 4.45% of listings.

Online delivery trends:

Only 2 out of 15 countries offer online delivery.

28.01% of Indian restaurants and 46.67% of UAE restaurants provide this service.

City-level insights (India):

Connaught Place, New Delhi – most restaurants listed (122), followed by Rajouri Garden (99) and Shahdara (87).

Most popular cuisine in Connaught Place: North Indian.

Only 54/122 restaurants in Connaught Place offer table booking.

Restaurants with table booking have an average rating of 3.9, compared to 3.7 for those without.

Best moderately priced restaurant:

Criteria: Cost for two < 1000, Rating > 4, Votes > 4, Indian Cuisine, Offers both table booking & online delivery.

Result: "India Restaurant" in Kolkata (RestaurantID: 20747).
