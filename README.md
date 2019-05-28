# Web Week

## Definitions

### Client

Software that accesses a service made available by a server. The server often being another computer system.

Examples:
 - Web browsers that connect to web servers.
 - Email clients that retrieve email from mail servers.

 You have thick clients which handle the bulk of data processing itself and doesn't necessarily rely on the server. E.g. a personal computer.

 You have thin clients which rely on the server to do the main data processing e.g. Office web apps.

### Server

A computer program that provides functionality for other programs or devices. This architecture is known as the client-server model.

Client-server systems are often implemented in a request-response model: a client sends a request to the server, which performs an action and sends it back to the client.

### HTTP

Hypertext Transfer Protocol is an application layer for transmitting hypermedia documents, such as html.

### HTTP Request/Response (Messages)

This is how data is exchanged between a server and a client.
Structure:
 - Start-line -> Requests to be implemented or its status whether successful or failure
 - HTTP Headers -> Specifying the request or describing the body included in the message.
 - Blank line -> indicates all the meta information has been sent
 - Body -> Optional data containing information about the request.

Requests trigger a process on the server that supplies a response.

### HTTP methods

Part of the start line of the http request.
Describes the action to be performed
 - GET
 - POST
 - HEAD
 - OPTIONS
 - DELETE
 - CONNECT
 - PUT

### HTTP Status Codes

HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes: informational responses, successful responses, redirects, client errors, and servers errors.

### Request Target

Usually a URL or absolute path to the server. E.g. GET /background.png HTTP/1.0

### API

API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you’re using an API.

### Application layer

An application layer is an abstraction layer that specifies the shared communication protocols and interface methods used by hosts in a communications network.
request/response

Examples:
 - TCP/IP application layer contains

### Ajax

Short for asynchronous JavaScript and XML.
A set of web development techniques using many web technologies on the client side to create asynchronous web applications.

Not a single technology, but a group of technologies.

HTML and CSS can be used in combination to mark up and style information. The webpage can then be modified by JavaScript to dynamically display—and allow the user to interact with—the new information.

By decoupling the data interchange layer from the presentation layer, Ajax allows web pages and, by extension, web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly utilize JSON instead of XML.

### cURL

A computer software project providing a library (libcurl) and command-line tool (curl) for transferring data using various protocols.

### MVC

Model - View - Controller
