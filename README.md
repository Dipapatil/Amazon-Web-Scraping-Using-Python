# Amazon-Web-Scraping-Using-Python

Contains 2 projects of Amazon web scraping

1. Scraping of Specific amazon product to get details like Title, Price, Rating and Date(scraping date) and store data into CSV file.
2. Get the list of best seller books for kids from amazon and store it into CSV file.

Tools used : Python, Jupyter Notebook

Web Scraping Notes :
	• Web scraping is the process of gathering information from the Internet

	• Request : -
	python -m pip install requests,
	The requests module allows you to send HTTP requests using Python and get the data


	• HTTP : 
	The Hypertext Transfer Protocol (HTTP) is the foundation of the World Wide Web, and is used to load web pages using hypertext links. HTTP is an application layer protocol designed to transfer information between networked devices 

	We get html code by requests , which is huge mess. So to parse that data we need Beautiful soup.

	• Beautiful soup :  is a Python library for parsing structured data

	• To install beautiful soup library

		Check version type on command prompt:
		Python --version

		Then install beautiful soup package

		Pip install beautifulsoup4

		Now we can import package in our code.

	• Pandas : pandas is a python library , it is use to analyze data.
	We can create data frame using padas. Which is 2 dimensional , we can print data in table format.
![image](https://user-images.githubusercontent.com/96765443/199791979-6deb5a32-36c6-4d74-90b7-224f46a3c3b3.png)
