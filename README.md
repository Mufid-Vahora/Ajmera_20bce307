##Ajmera Submission 20BCE307 Mufid Vahora

#Web Scraping Flipkart 

Web scraping is the process of automatically extracting information from websites. This can be done for various purposes, such as data mining, research, or building applications that require data from multiple sources.

#Libraries Used
pd: Pandas is a popular open-source data manipulation and analysis library for Python. It provides data structures for efficiently storing large datasets and tools for working with structured data. 
bs4: BeautifulSoup4, A Python library for pulling data out of HTML and XML files. It provides Pythonic idioms for iterating, searching, and modifying the parse tree.
requests: The requests library in Python is a popular HTTP library that simplifies sending HTTP requests and handling responses.

#Url
Searched 'mobiles' in flipkart search box.
url = 'https://www.flipkart.com/search?q=mobiles&otracker=search&otracker1=search&marketplace=FLIPKART&as-show=on&as=off'

#Handling Error Status codes
The web application handles the Error Responses status code.
So only a successful response (status code:200) executes the web crawling functionalities.

Data Storage:
A csv file is generated, which stores data such as Product Name, Product Price, Product Ratings and Product Features.

#Handling Different lengths of data
As lenghts of each data frame are different, I have taken the minimum amount of all dataframes (i.e. min(name,price,ratings,features)).
This will handle the null values too.











