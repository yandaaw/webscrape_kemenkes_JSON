# Web Scraping - Ministry of Health of the Republic of Indonesia for JSON file

<p align="center">
  <img width="500" height="200" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Logo_of_the_Ministry_of_Health_of_the_Republic_of_Indonesia.svg/250px-Logo_of_the_Ministry_of_Health_of_the_Republic_of_Indonesia.svg.png">
</p>
The Ministry of Health of the Republic of Indonesia(Kemenkes RI) is a ministry within the Government of Indonesia in charge of health affairs. The Ministry of Health is under and responsible to the President. The Ministry of Health is led by a Minister of Health(Menkes). The Ministry of Health has the task of carrying out government affairs in the health sector to assist the President in administering state government. In carrying out its duties, the Ministry of Health carries out the following functions:

1. Formulation, stipulation, and implementation of policies in the field of public health, disease prevention and control, health services, and pharmaceuticals, medical devices, and health workers. <br>
2. Coordinating the implementation of tasks, fostering, and providing administrative support to all organizational elements within the Ministry of Health.<br>
3. Management of state property which is the responsibility of the Ministry of Health. <br>
4. Supervising the implementation of tasks within the Ministry of Health. <br>
5. Implementation of technical guidance and supervision of the implementation of the affairs of the Ministry of Health in the regions. <br>
6. Implementation of the formulation and provision of health development policy recommendations. <br>
7. Implementation of substantive support to all organizational elements within the Ministry of Health. <br>

# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The main objective of this project is to gather information on hospital names, classes, types, owners, and status from the Ministry of Health's official website. The data will then be saved in a data frame and extracted into an excel or CSV dataset.

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**Selenium**](https://selenium-python.readthedocs.io/)
- [**Request**](https://docs.python-requests.org/en/latest/)
- [**Beautiful Soup**](https://beautiful-soup-4.readthedocs.io/en/latest/)

# Getting Started
Selenium is an open source umbrella project for a range of tools and libraries aimed at supporting browser automation. It provides a playback tool for authoring functional tests without the need to learn a test scripting language. While Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work. last but not least is Requests, request allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**Beautiful Soup documentation**](https://beautiful-soup-4.readthedocs.io/en/latest/) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- Selenium <br>
  ```
  pip install selenium
  ```
- Beautiful Soup <br>
  ```
  pip install beautifulsoup4
  ```
- Request <br>
  ```
  pip install requests
  ```
