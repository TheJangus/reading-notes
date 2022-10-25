
## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?
- Representational State Transfer = architectural style for building distributed systems based on hypermedia; most common REST API implementations use HTTP as the application protocol

2. REST APIs are designed around  ____.
- resources, which are any kind of object, data, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.
- a URI that uniquely identifies that resource
- https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?
- POST, GET, PUT, PATCH, and DELETE

5. What should the URIs be based on?
- A URI must represent an object, uniquely and permanently
- a URI is that it represents a data object on the Internet. The URI must be unique so that it is a one-to-one match – one URI per one data object.

6. Give an example of a good URI.
- http://api.example.com/louvre/leonardo-da-vinci/mona-lisa

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- It's best to avoid/bad
- Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation

8. What status code does a successful GET request return?
- 200 OK

9. What status code does an unsuccessful GET request return?
- 400 Bad Request

10. What status code does a successful POST request return?
- 200: OK - means that the request was received, understood, and is being processed
- 201 - indicates that a request was successful and a resource was created as a result

11. What status code does a successful DELETE request return?
- 202 ( Accepted ) -- if the action will likely succeed but has not yet been enacted
- 204 (No Content) -- if the action has been enacted and no further information is to be supplied.


## Bookmark and Review
- [RegExr - Pay particular attention to the cheatsheet](https://regexr.com/)
- [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
- [Regex 101](https://regex101.com/)
