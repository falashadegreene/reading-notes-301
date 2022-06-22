## API Design Best Practices 


What does REST stand for? Respresentational State Transfer

REST APIs are designed around a _resource___.

What is an identifier of a resource? Give an example. is a URL that uniquely identifies that resource. example url:  ` https://adventure-works.com/orders/1`

What are the most common HTTP verbs? the most common operations are GET, POST, PATCH, and DELETE

What should the URIs be based on? to uniquely and reliably name resources on the Web.

Give an example of a good URI. example: //192.0.2.16:80/.

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  chatty API's that expose a large number of small resources, such an API may require a client application to send mulitple request to find all of the data that is required. 

What status code does a successful GET request return? it returns a HTTP status code 200(OK)

What status code does an unsuccessful GET request return? it returns a HTTP status code 204 (NO Content)

What status code does a successful POST request return? it returns HTTP status code 200 and includs results of the operation in the response body.

What status code does a successful DELETE request return? HTTP status code 400 (Bad Request)
