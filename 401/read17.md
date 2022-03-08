# Spring Boot and OAuth2


## Summary of key features
---

### Key features

1. simple: a very basic static app
2. click: adds an explicit link that the user has to click to login.
3. logout: adds a logout link as well for authenticated users.
4. two-providers: adds a second login provider so the user can choose on the home page which one to use.
5. custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.

### How to Add a Local User Database

- Many applicaations need to hold data about their users locally, even if authentication is delegated to an external provider.

- Choose a backend for your database, and set up some repositories for a custom `User` object that suits your needs and can be populated, fully or partially, from external authentication.

### Adding an Error Page for Unauthenticated Users

- On the client, you might like to provide some feedback for a user that could not authenticate. To facilitate this, you can add a div to which you’ll eventually add an informative message.

- To support the retrieval of an error message, you’ll need to capture it when authentication fails. To achieve this, you can configure an `AuthenticationFailureHandler`.

### Conclusion

- All of the sample apps can be easily extended and reconfigured for more specific use cases.
- Remember to not put client credentials in source control.


## Things I want to know more about

---


## Resources/Citations

---

-[Spring and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
