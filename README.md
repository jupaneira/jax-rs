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
