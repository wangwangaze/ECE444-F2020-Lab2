# Zhuoer (Annie) Wang
This repo is a clone of https://github.com/miguelgrinberg/flasky

## Activity 1: Virtualenv and Flask Installed
![Alt text](./Import-Flask.png?raw=true)

## Activity 2: Example 2-2 
![Alt text](./Hello-Annie.png?raw=true)

## Activity 3: What are Flask global context variables?
### Request Context: 

A Request object called **request** containing the environment it received from the WSGI server is made for every request. The request data is global during the handling of the request.

A dictionary called **session** is used by the application to store values that are remembered between requests.

### Application Context: 

The **current_app** function points to the application instance handling the current activity, it can be used to access data about the running application, including the configuration.

The **g** object can be used by the application for temporary storage while handling requests. The object is reset for each new request.
