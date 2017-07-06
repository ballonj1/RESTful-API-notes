## RESTful Web Services
1. RESTful Web Services are basically REST Architecture based Web Services
-> In REST Architecture everything is a resource

REST stands for Representational State Transfer
1. REST is a web standards based architecture and uses HTTP Protocol for data communication
2. Revolves around resources where every component is a resource that is accessed by a common interface using HTTP standard methods

-> REST server provides ACCESS to resources
-> REST client ACCESSES and PRESENTS resources -> Each resource is identified by URIs/Global IDs
-> REST represents resources as Text, JSON, and XML

## RESTFul Web Services
-> Web Services are a collection of open protocols and standards used for exchanging data between applications or systems
1. Software apps written in different languages and running on different platforms can use web services to exchange data over computer networks like the Internet in a manner similar to inter-process communications on a single computer -> This is due to the use of open standards

* Web services based on REST Architecture are known as RESTful Web Services
1. Use HTTP methods to implement the concept of a REST architecture
-> A RESTful web service usually defines a URI (Uniform Resource Identifier), which is a service that provides resource representation such as JSON and a set of HTTP Methods

## What is a Resource
* REST architecture treats all content as a resource
* Can be Text Files, Html Pages, Images, Videos or Dynamic Business Data

## Good Resource Representation
1. REST imposes no restrictions on the format of a resource representation
2. Different clients can ask for different representations of the resource
* It is the responsibility of the REST server to pass the client the resource in the format that the client understands

## Messaging - HTTP Request and subsequent Response
1. RESTful Web Services uses HTTP to allow for communication between the client and server

HTTP Request

* Verb - Indicates the HTTP method such as GET, POST, DELETE, PUT
* URI - Uniform Resource Identifier to id the resource on the server
* HTTP Version - Indicates the HTTP version
* Request Header - Contains metadata for the HTTP Request message as key-value pairs.
-> Client (or browser) type, format supported by the client, format of the message body, cache settings, etc.
* Request Body - Message content or Resource representation

HTTP Response
* Status/Response Code - Indicates the Server status for the requested resource
* HTTP Version - Indicates the HTTP version.  For example HTTP v1.1
* Response Header - Contains metadata for the HTTP Response message as key-value pairs.
-> Content length, content type, response date, server type
* Response Body - Response message content or Resource representation

## Addressing
1. Refer to locating a resource or multiple resources lying on the server
2. Each resource in REST architecture is identified by its URI (locate the resource on the server hosting the web service)
-> VERB is the operation to be performed on the resource

* Constructing a Standard URI
1. Use Plural Noun
2. Avoid using spaces
3. User lowercase letters
4. Maintain Backward Compatibility - A URI once made public should always be available
5. Use HTTP Verb

A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.
