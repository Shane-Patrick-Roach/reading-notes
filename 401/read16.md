# Spring Security

## Spring Security Architecture

---

### Authentication and Access Control

- Applicaation security boilds down to two or more less independent prpblems: **authentication** and **authorization**.
- authentication = who are you?
- authorization = what are you allowed to do?

### Authentication

- `authenticationManager`
- `authenticationException` is a runtime exception. It is usually handled by an application in a generic way, depending on the style or purpose of the applicaation. In other words, user code is not normally expected to catch or handle it.
- `ProviderManager` delegates to a chain of authenticationProvider instances. 

### Authorization

- Once authentication is succesful. we can move to authorization and the core strategy her is `accessDecisionManager`.
- The  `Object` is a completely generic in the signatures of the `AccessDecisionManager` and `AccessDecisionVoter`.

### Web security

- Spring security in the web tier is based on Servlet `Filters`. 
- The client sends a request to the application, and the container decides which filters and which servlet apply to it based on the path of the request URL.
- At most, one servlet can handle a single reuest, but filters form a chain, so they are ordered.

## Spring Auth Cheat Sheet Summary

1. `setup a user model and repo`
2. `create a controller for that model`
3. `UserDetailsServiceImpl implments UserDetailsService` = gets a user from the databaase by username.
4. `Application User Implements UserDetails` = use intellJ to implmeent the methods; make the boolean ones all return true.
5. `WebSecurityConfig extends WebsecurityConfigurerAdapter`
6. `Registration Page` = create w/ form
7. `Login Page` = create w/ form

## Things I want to know more about

### How Does HTTP relate to Rest?

- Http is an application layer protocol for sending and recieiving messages over a network.
- We can use GET method for all sorts of interactions.
- REST is a specification that dictates how distributed systems on the web should communicate.

### How does The Web relate to REST? (Representation State Transfer)

- Rest is a concept invented by Roy Fielding
- Rest is the underlying architecture of the WEB.

### Questions every API should answer:

`How can the client tell the service provider which operation it wants to perform?`

- method information: The method information should be expressed in teh HTTP verb.
- scoping information should go in the URI.

### How a Restful API works?

- It uses HTTP methods suitably(GET,POST,PUT)
- scoping information goes in the parameters part of the URI
- It uses common data formats (most commonly JSON)
- Communication is statless.

### What is a URI

- URI = Uniform Resource Identifier
- Split into two classe, one that specifies Location and Name.

### What is a URL

- URL = Uniform Resource Locator
- Consists of two required components: The protocol and the the domain.
- `http` = protocol
- `://www.mywebsite.com` = domain 
-  `/hello` = path
- `?fn=flick&ls=Sidemack` = query parameters.


### What is a URN

- URN = Uniform Resource Name



## Resources/Citations
---

- [Spring Security](https://spring.io/guides/topicals/spring-security-architecture/)
- [Sprng Auth Cheat Sheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)
