# ASYNCHRONOUS JAVASCRIPT: PROMISES, ASYNC/AWAIT AND AJAX

## LECTURE ASYNCHRONOUS JAVASCRIPT, AJAX AND APIS

### WHAT IS SYNCHRONOUS CODE

Synchronous simply means that the code is executed line by line in the exact order of execution that we define in our code

Each line of code always waits for the previous line to finish execution.

This create problems when one line of code takes a long time to run.

example an alert window will block code execution, so nothing will happen on the page until we click the OK Button An only then the code can continue executing

The alert statement is an example of a long running operation which blocks execution of the code

Most of the time synchronous code is fine and makes perfect sense
But imagine that execution would have to wait for example for a five second timer to finish
Nothing on the page would work during these five seconds.
That's where synchronous code comes into play

- Most code is **Synchronous**
- Synchronous code is **executed line by line**
- Each line of code **waits** for previous line to finish

### ASYNCHRONOUS CODE

- Asynchronous code is executed after a task that runs in the background finishes.
- Asynchronous code is non-blocking
- Execution doesn't wait for an Asynchronous task to finish its work.

Asynchronous Programming is all about coordinating the behaviour of our program over a certain period of time

Asynchronous means not occurring at the same time

callback functions are use to implement Asynchronous behaviour
However this does not mean that callback functions automatically makes code asynchronous
Event Listeners do not make code asynchronous

### AJAX Calls

- AJAX stands for Asynchronous JavaScript And XML,
- Allows us to communicate with remote web servers in an asynchronous way
- with AJAX we can request data from web servers dynamically

in practice we make AJAX calls in our code in order to request some data from a web server dynamically without reloading the page so that we can use that data in our application dynamically

#### How AJAX works

So let say we have our JavaScript application running in the browser which is also called the client. And we want the application to get some data from a web server with Ajax we can do an HTTP request to the server which has this data and the server will then send back a response containing that data that we requested. This back and forth between Client and server all happens Asynchronously in the background. there can be different types of requests like GET request to receive data or post requests to send data to a server

when we ask a server to send us som data this server usually contains a web API this API is the one that has the data that we are asking for

### WHAT IS AN API

API stans for Application Programming Interface 

in general terms 
Piece of software that can be used be another software in order to allow applications to talk to each other and exchange information 

this is true for programming in general

in Javascript and web development there are countless 
types of APIs 
e.g DOM ApI, Geolocation API

These are called APIs because there are self contained piece of software that allow other pieces of software to interact with them

We can implement an API using a class