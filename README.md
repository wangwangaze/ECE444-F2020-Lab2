# Zhuoer (Annie) Wang
This repo is a clone of https://github.com/miguelgrinberg/flasky  
The application source code for lab 2 is located in hello.py

## Activity 1: Virtualenv and Flask Installed
![Alt text](./Import-Flask.png?raw=true)

## Activity 2: Example 2-2 
![Alt text](./Hello-Annie.png?raw=true)

## Activity 3: What are Flask global context variables?
### Request Context: 
The request context keeps track of the request-level data during a request. Rather than passing the request object to each function, it's globally accessible through request and session.

A Request object called **request** containing the environment it received from the WSGI server is made for every request. The request data is global during the handling of the request.

A dictionary called **session** is used by the application to store values that are remembered between requests within a user session.

### Application Context: 
The application context keeps track of the application-level data during a request, including configurations. Rather than passing the application to each function, it's globally accessible through current_app and g.

The **current_app** function points to the application instance handling the current activity, it can be used to access data about the running application, including the configuration.

The **g** object can be used by the application for temporary storage while handling requests. The object is reset for each new request.
