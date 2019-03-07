# Wiki-rest-api
wikipedia based Rest api built on node and express to perform http requests on articles


To run locally: <br>
npm i <br>
node app.js

use Postman or similar tools to send Restful requests 

examples: <br/>

GET http://localhost:3000/articles to fetch all articles

GET http://localhost:3000/articles/Bootstrap to fetch a specific article named Bootstrap

POST
http://localhost:3000/React
with title and content in body to add a new article named React

DELETE http://localhost:3000/React to delete an article named React
