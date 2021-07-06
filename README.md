<p align="center">
Module 10: Mission to Mars
</p>

<p align="center">
   <img src="https://user-images.githubusercontent.com/82583576/124536204-9317ec80-dde5-11eb-8f1f-0517e3442d8d.png"
</p>

   
A web application is designed to scrape various websites for data related to the Mission to Mars and displays the information in a single HTML page.

The following is an outline of how the data extraction was achieved and which tools were used.

**Phase 1: Data Collection and presentation**

Using Jupyter Notebook, Python, Beautiful Soup, Pandas and Splinter, multiple web sites were scraped to collect the following information:

1. The NASA Mars News site, redplanetscience.com, was scraped to collect the latest news headlines about Mars.
2. Featured images about the red planet was collected through the SpaceImages-mars.com website.
3. Facts related to Mars were collected by scraping the GalaxyFactsMars.com website. Such data was collected and presented in a DataFrame and stored in a Mongo Database.
4. Pictures about the four hemispheres of planet Mars were collected by scraping the MarsHemispheres.com website.
5. The above data was then published to a single web page using MongoDB, Flask, HTML as well as Bootstrap 3.

**Phase 2: Mars Hemispheres**
   
1. High resolution pictures scraped from MarsHemispheres.com were added to the webpage.
2. Using Bootstrap 3 components, styling, such as background colour, bolding of titles, sizing of images, sizing of column widths were applied to the web page.
3. Coding was also added to the HTML file to ensure the responsiveness of the page on multiple devices.

**The following is an illustration of the web page created.**
http://127.0.0.1:5000/
