# Express and Htmx

Messing about with Express and Htmx hosted on AWS. 

The express API just format the responses to 2 api calls to https://jsonplaceholder.typicode.com for notes and comments. 

Htmx calls these apis when the page loads so there is no javascript in the client.

## see

https://htmx.org

https://expressjs.com

https://docs.aws.amazon.com/amplify/latest/userguide/deploy-express-server.html

## to build 

`npm run dev`


if npm run dev crashes `[nodemon] app crashed - waiting for file changes before starting...` `pkill -f node`