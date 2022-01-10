# Mission-To-Mars
Robin, who loves astronomy and wants to work for NASA one day, has decided to use a specific method of gathering the latest data: web scraping. Using this technique, she has the ability to pull data from multiple websites, store it in a database, then present the collected data in a central location: a webpage. 

# Background :

A junior data scientist Robin does freelance astronomy work in her spare time. Here dream is to land a position with NASA someday. She spends a lot of time visiting websites with information and news about space exploration especially the mission to Mars. One day while reading an article about how much water MARS may have had, she has an idea. She wants to write a script that can gather all the information that she searches for in one convenient location. Once she gathers it she would like to show it to other astrophiles. If its polished enough, it may get NASA's attention too. After thinking about it, she moved=s ahhead with the decision to work on this project. She plans to build a web application that will scrape new data every time she tells it to with the click of a button. She will write a python script that can navigate the webpages to collect the right infor. Once she has the data, she will need to store it in one location. Robin will be using a NoSQl database, MongoDb because data pulled from the internet comes in different forms. Its not always in the neat and tidy tables that SQL requires. MongoDb is designed as a document based database that suits Robin's needs better. She will be downloading all sorts of datas including tables, paragraphs and images etc. To put it all together in a web application of her own, robin will need Flask. flask is a web framework that allows her to create a web app using python an dthen customize it with HTML and CSS. She has also decided to create a portfolio to showcase her  projects especially this one. She is going to use Bootstrap so that she can put a link to her portfolio on her resume.


# Procedure : 

Robin, who loves astronomy and wants to work for NASA one day, has decided to use a specific method of gathering the latest data: web scraping. Using this technique, she has the ability to pull data from multiple websites, store it in a database, then present the collected data in a central location: a webpage.

# Tools Used :

Web scraping is a method used by organizations worldwide to extract online data for analysis. Large co
employ web scraping to assess their reputations or track their competitors' online presence.
On a smaller scale, web scraping automates tedious tasks for personal projects.


![data-10-1-1-1-use-the-web-scraping-method-extract-into-mongo](https://user-images.githubusercontent.com/23488019/148616782-98d2d5ab-c80b-411d-8847-5f30d4a985ee.png)

1. HTML is a coding language used for creating webpages. It’s built using specific tags and arranging them in a nested order, a bit like building blocks.

2. Robin has decided to practice identifying specific data using Chrome Developer Tools (also known as DevTools). This tool allows developers to look at the structure of any webpage. 

3. Splinter
Splinter is the tool that will automate our web browser as we begin scraping. This means that it will open the browser, visit a webpage, and then interact with it (such as logging in or searching for an item). 

4. MongoDB (Mongo for short) is a non-relational database that stores data in Binary JavaScript Object Notation (JSON), or BSON format. A Mongo database contains collections. These collections contain documents, and each document contains fields, and fields are where the data is stored.

While Mongo and SQL are both databases, that's where the similarities end. They handle documents differently, the storage model isn't even close, and we even interact with them in very different ways.

# Libraries installed :
- Flask-PyMongo
- html5lib (Used to parse HTML in Python)
- lxml (Used to parse HTML in Python)
- PyMongo
- BeautifulSoup(bs4)
- webdriver_manager
- splinter