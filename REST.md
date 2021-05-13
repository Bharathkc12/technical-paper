# REST

REST stands for **REpresentational State Transfer**. It is an architectural style that defines a set of constraints to be used for creating web services. It is one of the most popular application program interfaces (API). A web service that follows these constraints is called *RESTful*. It relies on stateless, client-server protocol, and almost always uses *HTTP*.

**HyperText Transfer Protocol(HTTP)** is an application layer protocol used for data communication on the world wide web. HTTP is a stateless protocol meaning that the HTTP server will not remember whether a client has visited it before or how many times.

**REST** is preferred over **Simple Object Access Protocol(SOAP)** because REST uses less bandwidth, simple and flexible. It's used to fetch or give information from web services. In a *RESTful* web service, *HTTP* requests are made to fetch resources.

The responses are provided formatted in HTMP, XML, JSON, or some other format. HTTP methods(or verbs) are used to manipulate the resource. Here resources can be something that users want to fetch or modify. Some of the HTTP methods are GET, POST, PUT, and DELETE.

## GET

The HTTP GET is used to retrieve a resource in a format. The format can be XML, JSON, or some other format. In an error case, it returns a 404(NOT FOUND) or 400(BAD REQUEST).

### Example

<p>http://mysite.com/api/users</p>

Here the resource is users. The requests are made using the HTTP protocol.

## POST

The HTTP POST is used to store the data onto the resource. It is used when uploading a file or submitting a web form.

### Example

<p>http://yoursite.com/api/users</p>

The users resource is being modified.

## PUT

The HTTP PUT is used to create or update the resource at URI contained in the request.

### Example

<p>http://mysite.com/api/users/1</p>

The users resource with id 1 is created or updated based on the requirement.

## DELETE

The HTTP DELETE is used to delete a resource identified by a URI.

### Example

<p>http://mysite.com/api/users/1</p>

The users resource with URI 1 will be deleted.

## IDEMPOTENCE

An idempotent HTTP method is an HTTP method that can be called many times without different outcomes.

## References

* [https://en.wikipedia.org/wiki/Representational_state_transfer](https://en.wikipedia.org/wiki/Representational_state_transfer)
* [https://www.geeksforgeeks.org/rest-api-introduction/](https://www.geeksforgeeks.org/rest-api-introduction/)
* [https://www.youtube.com/watch?v=qVTAB8Z2VmA](https://www.youtube.com/watch?v=qVTAB8Z2VmA)
* [https://www.youtube.com/watch?v=Q-BpqyOT3a8](https://www.youtube.com/watch?v=Q-BpqyOT3a8)