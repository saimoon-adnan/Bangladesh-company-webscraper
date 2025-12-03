Web Scraping Bangladesh Company Data (Wikipedia Table Scraper)

This project extracts company information from the Wikipedia page
“List of companies of Bangladesh” and converts all tables into clean and structured CSV files.
It demonstrates skills in web scraping, data cleaning, pandas, and BeautifulSoup.

 --Project Overview--

This project scrapes:

✔ All tables from Wikipedia 
✔ Extracts table headers & rows
✔ Cleans the data 
✔ Saves each table into separate CSV files 
✔ Displays DataFrames inside Jupyter Notebook

It’s perfect for learning and showcasing web scraping skills.

 --Technologies Used--
Python 3
BeautifulSoup (bs4)
Requests
Pandas
Jupyter Notebook

--Project Structure--
📁 Bangladesh-Web-Scraper/
│── scraper.ipynb
│── data/
│    ├── table_1.csv
│    ├── table_2.csv
│    ├── ...
│── README.md
│── requirements.txt



--How It Works--
Send an HTTP request to Wikipedia
Parse HTML using BeautifulSoup
Locate all <table class="wikitable">
Extract header + row data
Convert to Pandas DataFrame
Save DataFrames into CSV files

--Purpose of This Project--
This project is ideal for:
Learning web scraping
Portfolio preparation
Data analysis practice
GitHub demonstration
Understanding HTML parsing

--Run the code--
pip install -r requirements.txt
jupyter notebook

--Author--
Saimoon Adnan









