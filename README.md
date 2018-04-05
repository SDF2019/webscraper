##  Web Scraper (CNN)  
A Node.js & MongoDB web-app that web-scrapes news data from [cnn](https://www.cnn.com/) and allows users to comment. Users can also delete unwanted comments. The deployed version is hosted in Heroku here!

##  Functionality

This app is using express to serve routes and mongoose to interact with a MongoDB database, on the backend. The app is also using handlebars for templating each article and materialize as a styling framework. In addition to the technologies named above its using jQuery and AJAX to help with making post requests. For web scraping, the app uses the request and cheerio node packages. All web scrapping code can be found within the controllers.js file.
