# WRRC and Java

## Example 

Example

`<protocol>://<host><:optional port>/<path/to/resource><?query>. `

An example is:
`|http|://|www.example.com||:5000||/mainpage||?query=param&query2=param2|`


### Method of Performing HTTP requests in Java.

1. `HttpUrlConnection` class allows us to perfrom basic HTTP requests without the use of any additional libraries.

THe disadvantages of this are that the code can be more cumbersome than other HTTP libraries and that it does not provide more advance functionalities such as dedicaated methods for adding headers or authentication.

2. Creating a Request. We can create a `httpURLConnection` instance using the openConnection() methods of the URL class. 

`URL url = new URL("http://example.com");
HttpURLConnection con = (HttpURLConnection) url.openConnection();
con.setRequestMethod("GET");`

### 3.Adding Request parameters. 

If we want to add paarameters to a request. We have to perform another series of operations. To facilitate the transformaation of the parameter Map, we have written a utility class called `parameterStringBuilder` containing a static method. THis transforms a Map into a String of the required format.

## Things I want to Know More About



## Reference/Citations

- [HTTP Review](https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-)
- [Simple Response Cycle](https://www.baeldung.com/java-http-request)
