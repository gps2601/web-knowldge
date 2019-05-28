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

### Request Target

Usually a URL or absolute path to the server. E.g. GET /background.png HTTP/1.0

### Application layer

An application layer is an abstraction layer that specifies the shared communication protocols and interface methods used by hosts in a communications network.
request/response

Examples:
 - TCP/IP application layer contains
