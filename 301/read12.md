# Reading 12


## Status Codes Based On REST Methods


### 100’s =

- Information status codes.
- Could signify the request will fail before the request is even made.

### 200’s =

- Success codes
- Met all validation requirements at the time of sending

### 300’s =

- redirection codes
- Lets the client know that the queried resourse is not availble anymore.

### 400’s =

- Error codes
- Clients is sending incorrect input
- Tells client to recheck input

### 500’s =

- Server error codes
- Best for client to retry same request.
- Could indicate the server is overwhlemed with requests at that time. 

### What is a status code 202?

- Often used for ***asynchronous*** processing. The request is currently processing and will finish sometime in the future.

### What is a status code 308?

- Permanent Redirect. Signigies the resource will be availble at a new URL and the client should directly access it via the new URL in the future.

### What code would you use if an update didn’t return data to a client?

- **204 code**.

### What code would you use if a resource used to exist but no longer does?

- **410 Gone**.

### What is the ‘Forbidden’ status code?

- **403** Forbidden. The client does not have permission to access the resource.

## Additional Resources

### Videos

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- Because this will allow us to conncet to our mongo Database.

### What is middleware?

- Middleware helps developers build applications more efficiently. It acts like connective tissue between applications, data, and users.

### What does app.use(express.json()) do?

- built in method in express to recognize the incoming Request Object as a JSON object.

### What does the /:id mean in a route?

- The id property of the ELement interface represents the elements identifier. If the id valye is not the empty string, it must be unique in a document. 



### What is the difference between PUT and PATCH?

- Put is a method of modifying resource where the client send data that updates the entire resource. 
- Patch is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

### How do you make a default value in a schema?

`
const schema = new Schema({
  name: String,
  role: { type: String, default: 'guitarist' }
});
`
- Mongoose only applies a default if the value of the path is trictly `undefined`.


### What does a 500 error status code mean?

- Internal Service Error, which could be anything from a missing header field the backend accessed without checking its existence. 

### What is the difference between a status 200 and a status 201?

- 201 signifies that the backend-side resource creation was succesful with a `location` header.

## Things I want to know more about

- Review the meaning of CRUD
- Review Post, Put, Patch, Update, Delete.

## Citations and References

- [Status Codes beased on REST methods]('https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/')
- [Video on Rest method]('https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw')
