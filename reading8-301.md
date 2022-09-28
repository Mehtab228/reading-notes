# APIs

## -------

### *What does REST stand for?

- Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP

### *REST APIs are designed around a ____

- REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

- A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be

- Clients interact with a service by exchanging representations of resources. Many web APIs use JSON as the exchange format. For example, a GET request to the URI listed above might return this response body

- REST APIs use a uniform interface, which helps to decouple the client and service implementations. For REST APIs built on HTTP, the uniform interface includes using standard HTTP verbs to perform operations on resources. The most common operations are GET, POST, PUT, PATCH, and DELETE

- REST APIs use a stateless request model. HTTP requests should be independent and may occur in any order, so keeping transient state information between requests is not feasible. The only place where information is stored is in the resources themselves, and each request should be an atomic operation. This constraint enables web services to be highly scalable, because there is no need to retain any affinity between clients and specific servers. Any server can handle any request from any client. That said, other factors can limit scalability. For example, many web services write to a backend data store, which may be hard to scale out. For more information about strategies to scale out a data store, see Horizontal, vertical, and functional data partitioning.

- REST APIs are driven by hypermedia links that are contained in the representation. For example, the following shows a JSON representation of an order. It contains links to get or update the customer associated with the order

### *What is an identifier of a resource? Give an example

- A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

https://adventure-works.com/orders/1

### *What are the most common HTTP verbs?

- GET, POST, PUT, PATCH, and DELETE

### *What should the URIs be based on?

- URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

### *Give an example of a good URI

- https://adventure-works.com/orders

### *What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- Another factor is that all web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires

### *What status code does a successful GET request return?

- A successful GET method typically returns HTTP status code 200 (OK)

### *What status code does an unsuccessful GET request return?

- If the resource cannot be found, the method should return 404 (Not Found).

- If the request was fulfilled but there is no response body included in the HTTP response, then it should return HTTP status code 204 (No Content); for example, a search operation yielding no matches might be implemented with this behavior

### *What status code does a successful POST request return?

- If a POST method creates a new resource, it returns HTTP status code 201 (Created). The URI of the new resource is included in the Location header of the response. The response body contains a representation of the resource

### *What status code does a successful DELETE request return?

- If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content)