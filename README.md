# nikeAPI
API endpoints for nike interview quesiton


 We’d like you to use NodeJS and ExpressJS to create a RESTful API with two endpoints. One of the endpoints should be handled with a callback and the other with a Promise.

In order to do this you will need to simulate some asynchronous process. Simulate this however you want, you can even use a simple timeout, but use your imagination.

Routes:

 

    /sample/callback
        Handled with a callback
        Returns a 200 response code and  JSON body: {“message” : “Hello Callback!”}
    /sample/promise
        Handled with a Promise
        Returns a 200 response code and JSON body: {“message” : “Hello Promise!”}

 

Make sure to handle your errors! In the case of either endpoint throwing an error you should return a 500 error response code and return a json response body: { “error” : “<insert error message here>”}.
