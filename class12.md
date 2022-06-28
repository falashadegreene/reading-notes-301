# Status Codes Based On REST Methods

## In your own words, describe what each group of status code represents

- 100’s = The client can continue the request or ignore if the request is already finished
- 200’s = 200's are succesful responses
- 300’s = This means there are more than one response. the user can choose one of the responses
- 400’s = This is a bad request error. The server will not process the request
- 500’s = Internal server error. the server has an error it can't handle.

1. What is a status code 202? The requested has been received but not yet acted upon.

2. What is a status code 308? It means that the resource is now permanently located at another URI, specified by the location.

3. What code would you use if an update didn’t return data to a client? code 204

4. What code would you use if a resource used to exist but no longer does? code 301
5. What is the ‘Forbidden’ status code? This indicates that the server understood the request but refuses to authorize it.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

2. What is middleware? is software that provides common services and capabilities to applications outside of what is offered by the operation system.

3. What does app.use(express.json()) do? it parses incoming JSON requests and puts the parsed data in req.

4. What does the /:id mean in a route? It is a number that uniquely identifies the route
5. What is the difference between PUT and PATCH? PUT is a method of modifying resource where the client sends data that updates the entire resource. PATCH is method of modifying resources where the client sends partial data.

6. How do you make a default value in a schema? by specifying a default value for an item by using the default keyword.

7. What does a 500 error status code mean? Internal server error
8. What is the difference between a status 200 and a status 201? according Mdn docs 200 The request succeeded. 201 means the request succeeded, and new resource was created as a result.