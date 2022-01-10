# Mission-To-Mars
Robin, who loves astronomy and wants to work for NASA one day, has decided to use a specific method of gathering the latest data: web scraping. Using this technique, she has the ability to pull data from multiple websites, store it in a database, then present the collected data in a central location: a webpage. This is a Flask web application that scrapes different websites for information related to Mars and displays all of the collected information in an HTML page.

## Background :

A junior data scientist Robin does freelance astronomy work in her spare time. Here dream is to land a position with NASA someday. She spends a lot of time visiting websites with information and news about space exploration especially the mission to Mars. One day while reading an article about how much water MARS may have had, she has an idea. She wants to write a script that can gather all the information that she searches for in one convenient location. Once she gathers it she would like to show it to other astrophiles. If its polished enough, it may get NASA's attention too. After thinking about it, she moved=s ahhead with the decision to work on this project. She plans to build a web application that will scrape new data every time she tells it to with the click of a button. She will write a python script that can navigate the webpages to collect the right infor. Once she has the data, she will need to store it in one location. Robin will be using a NoSQl database, MongoDb because data pulled from the internet comes in different forms. Its not always in the neat and tidy tables that SQL requires. MongoDb is designed as a document based database that suits Robin's needs better. She will be downloading all sorts of datas including tables, paragraphs and images etc. To put it all together in a web application of her own, robin will need Flask. flask is a web framework that allows her to create a web app using python an dthen customize it with HTML and CSS. She has also decided to create a portfolio to showcase her  projects especially this one. She is going to use Bootstrap so that she can put a link to her portfolio on her resume.


![data-10-6-1-1-storyboard-for-robin-app](https://user-images.githubusercontent.com/23488019/148723510-99596694-6186-424f-81ef-0ca5c996ed82.png)



## Procedure : 
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, we will use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images. 


![data-10-5-3-1-flowchart](https://user-images.githubusercontent.com/23488019/148723548-a62c89e4-c406-4345-8bbf-d952974421e2.png)


This  assignment consists of three technical analyses consisting of the following deliverables:

1. Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
2. Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles
3. Deliverable 3: Add Bootstrap 3 Components - Here we added various Bootstrap elements such as created a striped table, added a container
    - 

## Tools Used :

Web scraping is a method used by organizations worldwide to extract online data for analysis. Large companies employ web scraping to assess their reputations or track their competitors' online presence. On a smaller scale, web scraping automates tedious tasks for personal projects.


![data-10-1-1-1-use-the-web-scraping-method-extract-into-mongo](https://user-images.githubusercontent.com/23488019/148616782-98d2d5ab-c80b-411d-8847-5f30d4a985ee.png)

1. HTML is a coding language used for creating webpages. It’s built using specific tags and arranging them in a nested order, a bit like building blocks.

2. Robin has decided to practice identifying specific data using Chrome Developer Tools (also known as DevTools). This tool allows developers to look at the structure of any webpage. 

3. Splinter
Splinter is the tool that will automate our web browser as we begin scraping. This means that it will open the browser, visit a webpage, and then interact with it (such as logging in or searching for an item). 

4. MongoDB (Mongo for short) is a non-relational database that stores data in Binary JavaScript Object Notation (JSON), or BSON format. A Mongo database contains collections. These collections contain documents, and each document contains fields, and fields are where the data is stored.

While Mongo and SQL are both databases, that's where the similarities end. They handle documents differently, the storage model isn't even close, and we even interact with them in very different ways.

5. Flask  is a web microframework that helps developers build a web application. The Pythonic tools and libraries it comes with provide the means to create anything from a small webpage or blog or something large enough for commercial use.

## Libraries installed :
- Flask-PyMongo
- html5lib (Used to parse HTML in Python)
- lxml (Used to parse HTML in Python)
- PyMongo
- BeautifulSoup(bs4)
- webdriver_manager
- splinter
- Pandas
- Flask

## Database Used :

MongoDB was used to store the scraped data. To run locally, MongoDb is installed at the system. Next, run the command mongod on bash. We need to keep this tab open and active so that the Mongo instance continues to run. While Mongo does have a GUI, similar to pgAdmin for Postgres, we'll be using a command line interface (CLI) to make connections within the database. In our terminal, create a second window or tab to use for working in Mongo. Again, make sure your environment is active.

On the first line of this new window, type "mongo." This is done in a new window because, after you execute the command, you cannot use the terminal for other tasks—only to send information to and from the database.

After executing the command, your terminal will show a right angle bracket and a blinking cursor. This indicates that the database is active and ready for use.
We'll access data stored in Mongo the same way we access data stored in JSON files. This method of data storage is far more flexible than SQL's model.

## Websites used for Scrapping :

1. JPL Mars Space Images - Featured Image
The image url for the current Featured Mars Image is located and the url string of the full size image is assigned.

2. NASA Mars News
Here, the latest News Title and Paragraph Text is collected.

3. Mars Facts
Pandas is used to scrape the table containing facts about the planet including Diameter, Mass, etc. from the Mars Facts page.

4. Mars Hemispheres
From the Astrogeology site, full resolution images for each of Mars' hemispheres are obtained and displayed.

## Webpage :

![snapshot 1](https://user-images.githubusercontent.com/23488019/148728230-69369d9e-51bf-4e48-86cd-6d29b64f40dc.PNG)

## Mobile Responsive :

1. Snapshot of Mobile responsiveness for Iphone XR - 

![snapshot Iphone XR](https://user-images.githubusercontent.com/23488019/148728114-835c945f-cb32-4002-8520-a792f54a248d.PNG)

2. Snapshot of mobile responsivesness for Ipad Air - 

![snapshot Ipad Air toggle](https://user-images.githubusercontent.com/23488019/148728116-11f42c54-9b3e-4f15-96ad-3d02a36c85f6.PNG)

## Bootstrap components added extra:

1. Bold - <strong></strong> was added to the titles to make texts in bold format.
2. Bootstrap Heading - Bootstrap heading <h1></h1> to <h4></h4> were used to display texts in various sizes.
