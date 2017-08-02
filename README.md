# jax-rs
Project for a quick remainder-study about the REST WebServices in Java

REST full Web Services are one kind of WebServices. The principal differences with SOAP WebServices are:

* They don`t necessary stablish a formal contract to follow (wadl sometimes)
* They could use any format in order to exchange data (xml, json, csv, plain text)
* They make use of all of the HTTP Methods

So before starting with the REST ws itself, let's remind some aspects about Http

### HTTP
The Hypertext Transfer Protocol (HTTP) is an application protocol to exchange data over the network. 
We can clasify the http methods (the common ones) in two ways:

- Read Operations
  - GET
- Write Operations
  - POST
  - PUT
  - DELETE
  
 Another classification:
 
- Idempotent Operations (safely repeatable)
  - GET
  - PUT
  - DELETE
- No repeatable
  - POST (that's the reason because it is used to create data)
  
 #### HTTP Message Structure
 - Headers (metadata as the conten-type, message length, date, SATTUS-CODES!)
 - Body

 #### HTTP Status Codes
 - 1XX - Informational
 - 2XX - Success
 - 3XX - Redirection
 - 4XX - Client Error
 - 5XX - Server Error
 
### HATEOAS
**H**ypermedia **A**s **T**he **E**ngine **O**f **A**pplication **S**tate <br/>
Is a way to provide links to resources in the server response. The REST client doesn´t need any prior knowledge in order to interact with the server. In contrast with some SOA, there is no need of any fixed interface or contract. The server tells the necesary to the client through the responses
 
### Richardson Maturity Model
How RESTful is a WebService ? <br/>
- Level 3 - HATEOAS
- Level 2 - HTTP Methods
- Level 1 - Resource URI
- Level 0 - No RESTful (SOAP WebService)
 
 
   
  
