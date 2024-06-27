Project Title: Dynamic Dashboard for Scale Model Company
Duration:
March 2024 - April 2024 (2 months)

Project Overview:
This project involved the creation of a dynamic dashboard for a scale model company. The goal was to develop a dashboard that connects directly to a MySQL database, processes and visualizes the data using Microsoft PowerBI, and reflects on client needs by proposing new indicators to replace some KPIs that couldn't be achieved with the client's database.

Team Members:
Alexandre Borowski (Product Owner)
Emilienne Ekassi (Team Member)
Mykhailo Yermakov (Scrum Master)



Project Objectives:

Connect directly to a MySQL database
Utilize joins, views, and subqueries in SQL
Display the dashboard using Microsoft PowerBI
Understand client needs and propose new KPIs


Project Details:
  Data Connection:
    Connected to the company's MySQL database using read-only credentials.
    Created necessary SQL queries to extract and process data for the dashboard.

  SQL Queries:
    Utilized various SQL techniques including joins, views, and subqueries.
    The SQL queries file can be found in the repository (Requetes_SQL_.pdf).
  
  Dashboard Creation:
    The dashboard was created using Microsoft PowerBI, segmented into multiple tabs for different themes such as sales, finance, logistics, and human resources.
    Each tab contains visualizations and KPIs relevant to the respective theme.

  Key Performance Indicators (KPIs):
    Sales:
      Number of products sold by category and by month, with comparisons to the same month of the previous year.
    Finance:
      Revenue from orders in the last two months by country.
      Unpaid orders.
    Logistics:
      Stock of the top 5 most ordered products.
    Human Resources:
      Top 2 salespersons with the highest revenue each month.
  
  Tools and Technologies:
    SQL: For data extraction and manipulation.
    Microsoft PowerBI: For data visualization and dashboard creation.
    MySQL Workbench: For executing SQL scripts and managing the database.


Project Files:
Projet1.pbix: The PowerBI dashboard file.
Requetes_SQL_.pdf: Document containing all the SQL queries used.
Projet_Dashbord.pptx: Presentation slides for the project.
Usage Instructions:
Open the Projet1.pbix file in Microsoft PowerBI.
Refresh the data to get the latest updates from the MySQL database.
Navigate through the different tabs to explore various aspects of the company's data.
Challenges and Solutions:
Some KPIs were not achievable with the available data. We proposed alternative indicators and visualizations to fulfill the client's requirements.
Ensuring real-time data updates required setting up a robust connection between PowerBI and the MySQL database.
Future Improvements:
Automate the data update process to ensure real-time data availability.
Expand the dashboard to include more detailed and granular KPIs based on evolving client needs.
