# AWS and Cognito

## What is Cognito?

- The Amplify Auth category provides an interface for authenticating a user. Behind the scenes, it provides the necessary authorization to the other Amplify categories.
- It comes with default, built-in support for Amazon Cognito User Pool and Identity Pool.
- The Amplify CLI helps you to create and configure the auth category with an authentication provider.

## Registering a User

- The default CLI flow as mentioned in the getting started guide requires a username, password and a valid email id as parameters to register a user.

## Sign in as a User

- Implement a UI to get the username and password from the user.

## Multi-factor authentication

- Some steps in setting up multi-factor authentication can only be chosen during the initial setup of Auth. If you have already added Auth via the CLI, navigate to your project directory in Terminal, run amplify auth remove and when that completes, amplify push to remove it.

## Authentication with AWS

- In the Amplify ecosystem, the most common Authentication method is either using Amazon Cognito User Pools independently or with a social provider to validate the identity of the user (known as Federation).
- For many apps, user sign-up and sign-in is all that is needed. Once authenticated the app can talk to an API to access and mutate data.
- Some apps need to use AWS services which require signing requests. Examples of this would be storing images or videos on S3, or sending analytics to Pinpoint or Kinesis. 

## Resources/Citations
- [Cognito Docs](https://docs.amplify.aws/lib/auth/getting-started/)
