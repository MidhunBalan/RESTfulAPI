# RESTfulAPI
What is HTTP?

HTTP stands for Hyper Text Transfer Protocol

Protocol  :  Is a language or mechanism for communication
Hyper Text: The stuff that you exchange or transfer in HTTP is called Hyper Text
		  Hyper Text is a structured form of text
		  It contain logical link to the other text, this links are called the hyperlinks

RESTful API and Services
=========================
HTTP Methods
		Get-> Usually used to get some data from the server
		Post-> Usually used to post some data to the server
		Put -> Usually used to update the data
    Delete->To remove somthing
HTTP status code
200 -> Success
500 -> Server error
404 -> Not Found

Why we are using the error code?
To give the status of the request to the client like whether it is success or failure

Header values contain the metadata, for example, content type


Message Headers
Content types : example, application/json
				text/xml
Content negotiation

Key Points:
1. When you design RESTful API, you need to have resource based URIs
2. Need to choose Right HTTP methods for different actions
3. The response needs to return right HTTP status codes
4. All request and response should contain message headers.

Designing RESTful URI’s
========================
What is URI?

A Uniform Resource Identifier is a string of characters that unambiguously identifies a particular resource. 

There are two types of resource URI are available
1. Instance Resource URI
Identifies the Specific instance of a resource
2. Collection Resource URI
Represent a collection of resources
Query parameter for pagination and filtering collection
What is the use of Query parameter : For example, if you are fetching a lots of data at time, for example, fetching number of n number of messages, the client no need that much data and they just want to see the latest updates, then just go for Query parameters or else to fetch data based on the date range or for pagination purpose and all, we can go for query parameter.




