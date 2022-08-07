# Reading Notes class-12

Understanding general patterns and the way they are commonly used can make understanding tasks simpler.

## Status Codes Based On REST Methods

1. Status codes
- 100's = Usually indicate a high potential for failure based on part of the request, like mismatched protocol.
- 200's = Success codes. The input was validated and passed.
- 300's = Redirect codes. Used to indicate the information is no longer stored at the expected location.
- 400's = Client error codes indicating an invalid input.
- 500's = Server error codes. These indicate that the server was unable to fulfill the request.
2. The input was valid, but there may not be a successful response.
3. A permanent redirect to a new location.
4. 204
5. 410 Gone
6. client failed authorization test

## Build A REST API with Node.js, Express, & MongoDB

1. So it can be updated when it is changed to the deployed version.
2. Code that runs after the server gets a request, but before it is returned to the client.
3. Lets server accept JSON as the body.
4. A route for getting one user by id.
5. PUT is a full update. Patch is a partial update
6. A default schema is made by creating a model file with a schema for the properties of the data.
7. There was an error on the server side.
8. 200 is a default success, 201 specifically results from a successfully created resource.