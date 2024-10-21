# Web-Scrapping
This project focuses on web scraping, a technique to automate data extraction from websites. We chose to scrape news data from the BBC News World section using Python to gather valuable information like headlines, categories, and timestamps. The idea is to convert unstructured web data into a structured format (CSV) for further analysis.


# Tools and Approach:
Python is used for scripting, allowing easy integration of libraries.
BeautifulSoup parses the HTML content to find specific elements like headlines and categories.
Requests fetches the webpage’s content to be parsed.
Pandas helps in storing the extracted data in a DataFrame and exporting it to a CSV file.


# Workflow:
First, we send a request to the BBC News World page to get the HTML content.
Next, we use BeautifulSoup to parse the HTML and locate the elements containing the headlines, categories, and timestamps.
After extracting the data, we use Pandas to create a structured dataset and save it as a CSV file.
