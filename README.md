This project focuses on analyzing top-rated movies from The Movie Database (TMDB). The goal was to collect data from API and Web Scraping , clean and organize it using **Python**, store it efficiently in a **MySQL database**, and finally visualize the insights using **Power BI**. It was a great opportunity for me to apply the entire **data analytics** pipeline from end to end.

What I Did

1. **Data Collection**

    I used two main methods to gather movie data:

    • TMDB API: To get structured data like movie names, genres_id, ratings, vote counts, and popularity.

    • Web Scraping: For additional details such as genre_names, I used BeautifulSoup and Requests library to scrape data from the web.

2. **Data Cleaning & Preparation**

    Using **Pandas**, I performed:

    • Removal of duplicates and null values

    • Standardization of date and number formats

    • Extraction of nested fields like genres and production companies

    • Restructuring the data for better storage and analysis

3. **Data Storage**

    • After cleaning, I ingested the processed data into a **MySQL database**. This allowed for better management, querying, and integration with **Power BI**.

4. **Data Visualization**

    I connected Power BI to the MySQL database and created dashboards to analyze:

    • Rating trends over time

    • Most popular genres among top-rated movies

    • Popularity vs Rating comparison

Insights I Found

  • Drama was the most common genres among top-rated movies.

  • The early 1990s and 2010s saw a peak in high-rated movie releases. And after 2020s its dropping

  • Higher popularity didn't always mean better ratings.

Tools & Skills Used

  • **Python** for scripting and data processing

  • **TMDB API** + **Web Scraping** for data collection

  • **Pandas** for data cleaning and wrangling

  • **MySQL** for data storage and querying

  • **Power BI** for building interactive dashboards
