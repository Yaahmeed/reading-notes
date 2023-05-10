# APIs

## API Design Best Practices  

1. Representational State Transfer  

2. resources, which are any kind of object, data, or service that can be accessed by the client  

3. A resource has an identifier, which is a URI that uniquely identifies that resource. Ie: the URI for a particular customer order might be: (<https://company-name.com/orders/1>)

4. GET, POST, PUT, PATCH, and DELETE  

5. URIs should be based on the concept of resources (entities or objects) that the API exposes  

6. clearly indicate the relationship of resources ie: (<https://company-name.com/customer/order/1>)

7. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources.  

8. A successful GET returns 200  

9. An unsuccessful GET returns 4xx or 5xx  

10. A successful POST returns 201  

11. A successful DELETE reuturns 204  

[Learn Microsoft](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)  

## Things I want to know more about  
