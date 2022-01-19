# Reading 08





## API Design Best Practices

---

### What does REST stand for?

- Representational State Transfer

### REST APIs are designed around a ____.

- They are designed around **resources**. 
- Resources are a kind of object, data, or service that can be accessed by the client.

### What is an identifer of a resource? Give an example.

- A resources has an **identifier**
- This is aa URL that unqily identifies that resource. 

### What are the most common HTTP verbs?

- Get, Post, Put, Patch, Delete.

### What should the URIs be based on?

- Adapot a good consistent naming system in URIs. 
- In general Plural nouns for URIs that reference collections.
- Good practice to organize URIs for collections and items into a hierarchy.
- Keep them intuitive.

### Give an example of a good URI.

- /customers/5/orders
- /customers/1/orders/99/products replaced to /customers/1/orders


### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- THis is aa bad thing. Avoid "chatty" web apis that expose a large number of small resoucres. 
- Something could be chatty if it requires the client application to send multiple requests to find all of the data it requires.

### What status code does a successful GET request return?

- Get retrieves a representation of the resource at the specified URI.
- returns HTTP status code 200 (OK)

### What status code does an unsuccessful GET request return?

- Should return 404 (Not found)

### What status code does a successful POST request return?

- Returns a status code 201 (Created).

### What status code does a successful DELETE request return?

- 204 status code if no result to return.
- 400 if client provides invalid data.


## Things I want to Know More about

- Practice requesting and retreiving data from an API
- What is Get? - Retrieves a representation of the resource ar the specified URI. Body of response message contains the details of the requested resource.
- POST - creates a new resource at the specified URI. The body of the request message proves the details of the new resource.
- PUT - either creates or replaces the resource of the specified URI.
- PATCH - performs a partial update of a resources.
- DELETE - removes the resource at the secified URI. 


## References/Citations

-[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
