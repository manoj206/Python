A lot of data isn't accessible through data sets or APIs. This data may exist on the internet as web pages. However, one way to access the data without waiting for the provider to create an API is to use a technique called Web Scraping.

Web scraping loads a web page into Python so we can extract the information we want. We can then work with the data using standard analysis tools like pandas and numpy.

This folder includes a small hands-on python project on how to scrape the webpage details from an Ekart store : Amazon and store the extracted information to a CSV file for later analysis.
Any product that would be searched on this Ekart website(amazon.in), would give us a list of items. The goal of the project is to fetch each product specific details like name, price, reviews etc. and store all of them product details to a pandas dataframe via python dictionary. The dataframe can then be utilised for further data analysis or can also be converted to different file format like CSVs.
