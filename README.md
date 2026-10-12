✈️ Airline Ticket Price Analysis

📌 Project Overview

This project analyzes airline ticket pricing data to uncover pricing patterns and travel trends. Using Exploratory Data Analysis (EDA), SQL, and data visualization, the project explores how ticket prices vary across airlines, routes, travel classes, flight duration, and days left before departure.

The goal is to generate meaningful insights that support better understanding of airline pricing behavior and travel planning.

🎯 Objectives

Analyze ticket prices across different airlines.

Compare Economy and Business class pricing.

Study the relationship between ticket prices and the number of stops.

Identify routes with higher average ticket prices.

Examine how prices change based on days left before departure.

Analyze pricing patterns by flight duration and arrival time.

Present findings through clear visualizations and SQL queries.

📊 Dataset

The dataset contains 300,153 records covering six airlines and six Indian cities.

Key columns:

airline – Airline name

flight – Flight identifier

source_city – Departure city

departure_time – Departure time category

stops – Number of stops

arrival_time – Arrival time category

destination_city – Arrival city

class – Travel class

duration – Flight duration in hours

days_left – Days remaining before departure

price – Ticket price

🛠️ Tools & Technologies

Python: Data analysis and data cleaning

Pandas & NumPy: Data manipulation

Matplotlib & Seaborn: Data visualization

MySQL: SQL-based analysis

Jupyter Notebook: Exploratory data analysis

🔍 Analysis Performed

Dataset inspection and data quality checks.

Average ticket price comparison by airline.

Economy vs. Business class price analysis.

Price analysis by number of stops.

Route-wise average ticket price comparison.

Price trends based on days left before departure.

Flight duration and arrival-time price analysis.

💡 Key Insights

Ticket prices vary considerably across airlines and travel classes.

Business class tickets generally have higher average prices than Economy class tickets.

In this dataset, flights with one stop have a higher average ticket price than nonstop flights.

Ticket prices tend to be higher when departure is closer, although patterns vary by travel class.

Flight duration, route, and arrival-time category are useful dimensions for comparing ticket prices.

🚀 Project Status

The Python exploratory analysis and visualizations have been started. SQL analysis and further reporting can be added as the project progresses.

📁 Repository Structure

airline-ticket-price-analysis/
│
├── data/
│   └── fair_airline.csv
│
├── notebooks/
│   └── airline_price_analysis.ipynb
│
├── visualizations/
│
└── README.md

▶️ How to Run

Clone or download this repository.

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook.

Update the dataset file path if required.

Run the notebook cells to reproduce the analysis and visualizations.

📌 Conclusion

This project demonstrates how exploratory data analysis and SQL can be used to investigate airline ticket pricing patterns and extract business-relevant insights from a large dataset.

Note: This project focuses on data analysis and visualization, not machine learning or ticket price prediction
