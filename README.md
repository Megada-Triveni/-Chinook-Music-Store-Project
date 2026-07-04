# -Chinook-Music-Store-Project
Explores the Chinook database
📌 Project Overview

This project explores the Chinook database, a sample dataset representing a digital music store. It contains information about artists, albums, tracks, genres, customers, employees, invoices, and playlists — modeled after a real-world media store like iTunes.

The goal of this project is to practice and demonstrate SQL skills including data querying, joins, aggregation, subqueries, and business analysis through a relational database.

🗄️ Database Schema

The Chinook database consists of 11 core tables:

Table                    ||                 Description
------------------------------------------------------------------------------------------
artists                  ||     List of music artists
albums                   ||     Albums linked to artists
tracks                   ||     Individual songs/tracks with pricing, duration, genre
genres                   ||     Music genres
media_types              ||     File formats (MPEG, AAC, etc.)
playlists                ||     User-created playlists
playlist_track           ||     Join table linking playlists and tracks
customers                ||     Customer details
employees                ||     Store employees (including support reps)
invoices                 ||     Customer purchase invoices
invoice_items            ||     Line items for each invoice


🎯 Objectives


Practice writing SQL queries (SELECT, JOIN, GROUP BY, subqueries, CTEs, window functions)
Analyze sales trends, customer behavior, and top-performing artists/genres
Demonstrate database design understanding through relational schema exploration
Answer real-world business questions using SQL


🔍 Sample Business Questions Explored


Who are the top 5 best-selling artists by revenue?
Which genre generates the most sales?
Who are the top spending customers?
What is the average invoice total per country?
Which employee has generated the most sales?
What are the most popular playlists by track count?


🛠️ Tech Stack


Database: MySQL 
Tools: MySQL Workbench 
Language: SQL


📁 Repository Structure

chinook-music-store-sql/
├── README.md
├── schema.sql          # Database schema (tables, keys, relationships)
├── chinook_data.sql    # Sample data (or link to source if too large)
├── queries/
│   ├── sales_analysis.sql
│   ├── customer_insights.sql
│   └── employee_performance.sql
└── docs/
    └── chinook-erd.png

🚀 How to Use


Clone this repository


bash   git clone https://github.com/yourusername/chinook-music-store-sql.git


Import the schema and data into your database:


bash   mysql -u username -p database_name < schema.sql
   mysql -u username -p database_name < chinook_data.sql


Run the queries in the queries/ folder to explore insights.


📊 Key Insights (fill in after running your analysis)


Example: Rock is the top-selling genre, accounting for X% of total sales.
Example: The USA generates the highest total revenue among all countries.
