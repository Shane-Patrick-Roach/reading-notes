# Spring 

## Building a Simple Spring Application 
---
### Summary 
- Built a static homepage that accepts a GET request at `http://localhost:8080/greeting`
- In Spring's approach to building web sites, HTTP requests are handled by a controller. You can identify this by `@Controller` annotation. 
- The `@GetMapping` annotation ensure that HTTP GET requests to `/greeting` are mapped to the `greeting()` method.
- The implemetation of the method body relies on a view technology to perform server side renderings of the HTML. Thymeleaf pareses the `greeting.html` template and evaluates the `th:text` expression to render the value of the `${name}` paramter that was set in the controller. 

### Spring Boot Devtools

A common feature of developing web applications is coding a change, restatrting your application, and refreshing the browser to view the change. This eats up a lot of time. `spring-boot-devtools` allows
- enables **Hot Swapping**
- Switches template enginers to diable caching.
- Enables LiveReload to automatically refresh the browser.
- Other reasonable defaults based on development instead of production.

### Running the application 

If you use gradle you can run the applications by using `./gradlew bootRun`.

## Spring MVC and Thymeleaf: how to access data templates.

---

In a typical Spring application, @Controller claasses are responsible for preparing a model map with data and selecting a view to be rendereed. This makes all the defined variables availalbe to expressions executed in templates.

### Process includes

1. Spring Model Attributes
2. Request Parameters
3. Session Attributes
4. ServletContext Attributes
5. Spring beans


## Things I want to know more about

---

### HTTP protocol review
- HTTP => hyper text tranfer protocol
- HTTP is a connectionless protocol - after making the request. The client diconnects from the server.
- The http can deliver any sort of daata. as long as the two computers are ablt to read it.
- http is statless; the client and server know about each other just during the current request. If it closes, and the two computers want to connect again, they need to provide information to each other anew, and the connection is handles as the very first one.
- Was first designed to transfer HTML documents.
- A typical http message includes a Start line, Headers, and Body.
- The method is a command that tells the server what to do. Eg. GET, POST, PUT...
- The URI is a set of readable chaaracters and a way to locate the resources.
- Response http message. status code (tells client if the request succeeded or failed.), response body containes the information. 

### WRRC
- The Request Response Cycle
- CLient makes a request to the server, then disconnects, then hits server. 
-  The http is a statless, connectionless, and can deliver any data.
- Http response message differs from http request message. 


## Resources/Citations
---

- [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
- [Spring MVC and Thymeleaf](https://www.thymeleaf.org/doc/articles/springmvcaccessdata.html)
