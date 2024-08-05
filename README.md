RedBus Data Scraping with Selenium & Dynamic Filtering using Streamlit

Introduction

RedBus is a prominent online bus ticket booking platform in India with a wide network of bus operators. This project utilizes web scraping and dynamic filtering to collect, analyze, and visualize bus travel data from redBus.

Problem Statement

The "redBus Data Scraping and Filtering with Streamlit Application" project aims to streamline the collection and analysis of bus travel data from redBus. By using Selenium for scraping and Streamlit for dynamic filtering, this project enhances data-driven decision-making and operational efficiency in the transportation industry.

Packages Used

Selenium: Automates web browser interactions.
Streamlit: Converts data scripts into shareable web apps with Python.
Pandas: Provides data manipulation and analysis tools.
MySQL: Open-source SQL database management system.
PyMySQL: Library for connecting Python to MySQL.

Code Flow Plan

Step 1: Scrape Route Names and Links
Description: This step involves scraping route names and their corresponding links from the redBus website.
File: Red_bus_scraping_links&routes.ipynb
Modules Used: Selenium, Pandas

Step 2: Extract Detailed Bus Information
Description: In this step, detailed bus information such as bus name, type, route, link, departure and arrival times, rating, and price is extracted from the previously created CSV file.
File: data_scarping_from_links&routes.ipynb
Modules Used: Selenium, Pandas, Time

Step 3: Create MySQL Database
Description: This step involves creating a MySQL database and importing the data from the CSV file into this database.
File: connecting_to_sql_database_redbus.ipynb
Modules Used: Pandas, PyMySQL

Step 4: Develop Streamlit Web Application
Description: A Streamlit web application is developed to allow dynamic filtering and analysis of the collected data. This helps with business development, competition analysis, and price comparison.
File: streamlit.ipynb
Modules Used: Streamlit, Pandas, PyMySQL

How to Use the Application

•	Route Selection: Choose the route you are interested in from the dropdown.
•	Seat Type: Select your preferred seat type from the dropdown.
•	Price Range: Use the + and - buttons to adjust your budget range.
•	Star Rating: Use the + and - buttons to adjust the minimum star rating.
•	Starting Time: Select the desired departure time from the dropdown.
•	View Results: Results are displayed automatically based on your selections.

How to Run the Code

•	First, run the Red_bus_scraping_links&routes.ipynb notebook to scrape bus routes and their links.
•	Second, run the data_scarping_from_links&routes.ipynb notebook to extract detailed bus information.
•	Third, run the connecting_to_sql_database_redbus.ipynb notebook to connect the data to the MySQL database.
•	Final Step, run the streamlit.ipynb notebook to set up the Streamlit web application.
•	Launch the Streamlit App: To run the Streamlit application, type the following command in your terminal:  streamlit run app.py
