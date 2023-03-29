# Safar : An Application for booking flight Tickets & services related to AirTravel

# Safar-API-Gateway : 

FRONTEND  <-> MIDDLE-END <-> BACKEND

- We need an intermediate layer between the client side and the microservices
- Using this middle-end, when client sends request we will be able to make decision that which microservice should actually respond to this request
- We can do message validation, response transformation, rate limiting
- We try to prepare an API Gateway that acts as this middle end.

[DESIGN DOC](https://docs.google.com/document/d/18Az_VeNbd9sjkZpcMkdjBM1kimqoFTH1mbOeB14Z0Ow/edit?usp=sharing)


## Project Setup:
 - clone the project on your local ( git clone ... )
 - Execute `npm install` on the same path as of your root directory of the downloaded project
 - Make all the other services server started, 
 then run `node index.js` from the terminal
