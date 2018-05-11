### [Odata](http://www.odata.org)

![](cons/img/odata.png)


> <small>OData (Open Data Protocol) is an OASIS standard that defines a set of best practices for building and consuming RESTful APIs OData helps you focus on your business logic while building RESTful APIs without having to worry about the various approaches to define request and response headers, status codes, HTTP methods, URL conventions, media types, payload formats, query options, etc. OData also provides guidance for tracking changes, defining functions/actions for reusable procedures, and sending asynchronous/batch requests.</small>

> <small>OData RESTful APIs are easy to consume. The OData metadata, a machine-readable description of the data model of the APIs, enables the creation of powerful generic client proxies and tools.</small>




# ODATA
> OData the best way to REST


## Open Data Protocol
- SAP's chosen protocol to communicate data accross SAP systems
- A microsoft standard maintained by the OASIS Org.
- ISO Compliant
- Built on top of the REST (HATEOAS) discipline


#### Request
1. URI
  1. URL
  1. Parameters / Query Options
  ```
    $Select
    $Filter
    $Expand
    $OrderBy
    $top
    $skip
    $top
    $search
    $Format
    $compute
    $index
    $schemaversion
  ```


 Methods/Verbs
  - POST
  - GET
  - PATCH
  - DELETE


### ODATA in action within SAP
1. URI
  1. URL / SICF
  1. Parameters
    - ?
    - $ - query options
1. Methods
  1. Class Based Handling (SEGW/CL_HTTP_HANDLER)



## /IWFND/MAINT_SERVICE
- Service Maintenance
  - Add/Edit/Delete/Test services