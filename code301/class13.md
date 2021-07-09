

#  each group of status code represents
* 100’s =These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.
* 200’s = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.
* 300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location
* 400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.
* 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. 

### What is a status code 202?
The 202 response is intentionally non-committal. Its purpose is to allow a server to accept a request for some other process (perhaps a batch-oriented process that is only run once per day) without requiring that the user agent's connection to the server persist until the process is 

### What is a status code 308?

The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.
What code would you use if an update didn’t return data to a client?
204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.

### What code would you use if a resource used to exist but no longer does?
The HyperText Transfer Protocol (HTTP) 410 Gone client error response code indicates that access to the target resource is no longer available at the origin server and that this condition is likely to be permanent

### What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
replica set name and members in the connection string

### What is middleware?
Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.

### What does app.use(express.json()) do?
express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.

### What does the /:id mean in a route?
What is the difference beween PUT and PATCH?
The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.



### What does a 500 error status code mean?
The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This error response is a generic "catch-all" response.

### What is the difference between a status 200 and a status 201 ?
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page)