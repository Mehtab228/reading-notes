# CRUD

## --

### *In your own words, describe what each group of status code represents:

- 100: These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

- 200: These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending

- 300: These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

- 400: These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

- 500: These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

### *What is a status code 202?

- In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

### *What is a status code 308?

- Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them

### *What code would you use if an update didn’t return data to a client?

- 204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document

### *What code would you use if a resource used to exist but no longer does?

- 204 No Content - The most fitting status code for this case. It’s better to reduce traffic and simply tell the client the deletion is complete and return no response body (as the resource has been deleted)

### *What is the ‘Forbidden’ status code?

- 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource

### *Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- Because we won't be always running our backend on localhost

### *What is middleware?

- Middleware is code that runs when a server gets a request but before it gets passed

### *What does app.use(express.json()) do??

- Server accepts JSON as a body instead of a post element

### *What does the /:id mean in a route?

- it signifies that it is a paramter

### *What is the difference between PUT and PATCH?

- Path updates only based on what the user passes in, put updates all of the information rather than just what is passed in

### *How do you make a default value in a schema?

- You just typer default as a property and uses that if the user doesnt pass in the specific information

### *What does a 500 error status code mean?

- The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request

### *What is the difference between a status 200 and a status 201?

- 200 - OK:
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed.

- 201 - Created:
A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).