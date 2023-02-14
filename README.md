# CS-361
CS-361 repo
Adding this for the commit

To make a request to my microservice, send a POST request with a JSON body of the following format to create a meal entity:

{
  "name": "Casserole of the gods",
  "recipe": {"carrot": "1",
  "cookie": "2"}
}

Send the request to the endpoint https://meal-tracker-374718.uk.r.appspot.com/meals.

You will receive data back in the response body from the API with the object you just created, along with some additional parameters and of course a status code to tell youw the status of your request:

{
recipe: {
cookie: "2",
carrot: "1"
},
name: "Casserole of the gods",
probability: 1,
id: "5716561121771520",
self: "https://meal-tracker-374718.uk.r.appspot.com/meals/5716561121771520"
}

See the UML sequence diagram below for further clarification


![78E0EDB4-572B-4F42-BD2F-9F02C13D01DC](https://user-images.githubusercontent.com/83733825/218611743-ef5390c3-7fdc-4624-a3ce-6b8e27ffcfe4.jpeg)
