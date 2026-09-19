🏠 Airbnb Forecast Dashboard
Data Analytics Project (Power BI)

📌 Overview
This project demonstrates the use of Power BI to analyze Airbnb listings and customer reviews. The goal is to transform structured Airbnb data into interactive dashboards that highlight trends, KPIs, and insights about listings, hosts, property types, and customer ratings.

Unlike a full ETL pipeline project, this work focuses on data visualization and storytelling — showcasing how Power BI can turn cleaned datasets into actionable business insights.

🎯 Key Objectives
Load and explore cleaned Airbnb datasets (Listings & Reviews).

Build two interactive dashboard pages in Power BI:

Overview Page → High-level KPIs and trends.

Ratings Page → Customer review analysis and city-level comparisons.

Create measures in DAX to support deeper insights.

Highlight Airbnb’s growth trajectory, regulatory impacts, and pandemic effects.

Present findings in a clear, professional format.

📁 Dataset
Two structured datasets were used:

Listings dataset → Contains information about listings, hosts, property types, and cities.

Reviews dataset → Contains customer reviews, ratings, and feedback metrics.

Format: CSV / Excel
Data was cleaned and structured before importing into Power BI.

🛠️ Tools & Technologies
Tool	Purpose
Power BI	Dashboard creation & visualization
DAX	Measures & calculated insights
Excel/CSV	Source data


🔄 Project Workflow
Cleaned Dataset
↓
Import into Power BI
↓
Create DAX Measures
↓
Build Overview Dashboard
↓
Build Ratings Dashboard
↓
Extract Insights & Recommendations

📈 Dashboard Pages
1. Overview Page
KPIs (Cards): Listings, Cities, Hosts, Property Types, Reviews.

Line Chart: Count of listings by year.

Room Type Analysis: Measure created to compare room types.

Key Insight:

Airbnb reached its highest number of new listings in 2015.

Growth slowed in 2016–2017 due to local regulations.

Airbnb became profitable in late 2016–2017.

Growth resumed in 2018, but was halted in 2019 due to the pandemic.

2. Ratings Page
Stacked Column Chart: Total listings by city.

Line Chart: Total reviews trend.

Key Insight:

Paris, NYC, and Sydney account for nearly 50% of listings and 48% of reviews.

Paris leads both in listings and reviews, driven by hotel prices being nearly double Airbnb rates.

Bookmarks:

Overview Ratings → Stacked column chart + average rating by city.

Detailed Ratings → Matrix chart showing cleanliness, accuracy, communication, location, and value ratings by city.

📊 Key Results & Insights
Airbnb’s growth trajectory shows clear regulatory and pandemic impacts.

Paris, NYC, and Sydney dominate the platform in both listings and reviews.

Customer ratings highlight strengths in location and value, but variation exists across cities.

📂 Project Structure
Code
airbnb-forecast-dashboard/
│
├── data/
│   ├── listings.csv
│   └── reviews.csv
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── overview_page.png
│   └── ratings_page.png
│
└── README.md
▶️ How to Run
Clone the repository:

bash
git clone https://github.com/yourusername/airbnb-forecast-dashboard.git
cd airbnb-forecast-dashboard
Open dashboard.pbix in Power BI Desktop.

Update the data source paths if required.

Explore the Overview and Ratings pages interactively.

🎯 Skills Demonstrated
Power BI dashboard design

DAX measures for KPIs and insights

Data storytelling with bookmarks and interactive visuals

Business intelligence in the hospitality & travel domain

⭐ Project Goal
The goal of this project is to showcase Power BI skills by building a professional Airbnb dashboard that highlights growth trends, city-level performance, and customer ratings — turning raw data into actionable insights for business decision-making.
