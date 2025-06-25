Project: CBN Exchange Rate Data Scraping and Visualization

In this project, I worked on extracting and analyzing exchange rate data from the Central Bank of Nigeria (CBN) website, with the goal of tracking rate changes over time and visualizing the insights using Tableau.

Process Overview:
Data Discovery & Extraction:
I began by visiting the official CBN website to locate the exchange rate data. Using the browser's Inspect Element tool, I accessed the HTML structure of the webpage and identified the table containing the relevant information.

Web Scraping with Python:
After locating the data, I copied the HTML and used PyCharm to write a Python script that parsed and extracted the table using BeautifulSoup. This step allowed me to transform the raw HTML into structured, readable data.

Data Cleaning in Excel:
Once the data was extracted, I exported it into an Excel sheet. There, I conducted a quick analysis to check for any missing or inconsistent values and ensured the data was properly formatted for further use. This included checking date formats, numeric consistency, and ensuring column alignment.

Visualization in Tableau:
The cleaned dataset was then imported into Tableau for visualization. One of the main challenges here was dealing with the date formatting and ensuring that the visual timelines were accurate and meaningful. Despite the number of data points, I was able to create clear visuals showing trends, fluctuations, and insights over time.

Included Files:
The HTML file used for scraping

The Excel sheet containing cleaned and structured data

Visualizations created with Tableau (packaged or screenshot formats)
