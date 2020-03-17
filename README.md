# Custom Corner - Demo Site
[Custom Corner Demo Site](https://jhaarla.github.io/Custom-Corner-Demo/)
![Custom Corner Screenshot](https://jhaarla.github.io/Custom-Corner-Demo/assets/CustomCornerDemo.png)
The purpose of Custom Corner is to streamline an interior designer's workflow by aggregating data from various vendors and then sharing the collection with their clients. Since the live deployment of Custom Corner is used by a company and only allows authenticated users, this site serves as a demonstration of the app's functionality. Custom Corner is a full stack MERN (Mongo, Express, React, Node) app that scrapes various vendor's sites for data to be displayed. The user has the ability to filter through this aggregated data and make selections to be shared with their clients. Sharing can be done through Pinterest or there is a built-in PDF creator that makes sharing easy as well. Let's explore the functionality of Custom Corner!

## Infrastructure
Custom Corner is hosted on the Google Cloud platform and is currently using Docker to runb the application. There are multiple containers running on the server:
* Mongo - Houses the database for the application
* NGINX - performs reverse proxy and handles SSL. Also redirects http connections to https.
* Certbot - Automates renewing the SSL certification through Let's Encrypt
* Node - Runs the React app

## Technologies Used
### React
* Bootstrap-React
* React-Toastify
### Mongo
* Node - Mongoose
* Mongoose-bcrypt
* Python - pymongo
### Node
* JSON Web Token
### Scraping 
* NodeJS - Axios, Cheerio, Puppeteer
* Python - requests, BeautifulSoup (bs4)
### Design
* Figma

## Dev Team
* Jarkko Haarla
* Scott Daniels
* Greg Desmarais
* Jeff Greco
* Bradley Cordle
* Toney Higgins

[Custom Corner Demo Site](https://jhaarla.github.io/Custom-Corner-Demo/)