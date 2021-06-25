#eagleeyez

Eagleeyez is a web-based application designed to solve the lack of information accessible to PG county residents. With eagleeyez, residents can access up-to-date crime data via the search bar. Additionally, users can choose the type of crime they are inquiring about, input a street number and street address in order to identify the amount of crimes occurring in that area. The website would then present them with the number of [x] crimes that have occurred in that area. 

#eagleeyez Heroku Site
https://eagleeyez.herokuapp.com/
#Supported Browsers 
Chrome

#Installation
Have an up-to-date version of Node.js: (https://nodejs.org/)
use GitHub Desktop

#Dependencies
npm install
Npm packages include:
Express - Node.js server framework
Nodemon - Restart node server while coding changes

#Bugs
No security implemented

#Server API
Endpoints

https://data.princegeorgescountymd.gov/resource/wb4e-w4nf.json?.

PUT:
PUT requests can be submitted to /api
GET:
GET requests can be retrieved from /api
GET requests return a conformation string or an error message once completed

#Future Development 
We would like to expand the data from Prince George's County to all of Maryland by gathering data from all the Police department databases. Other features we would love to have are more filtering options, such as dates. We also want to eventually overlay our data on a map so that the user can visualize the data better and utilize the application more effectively.
