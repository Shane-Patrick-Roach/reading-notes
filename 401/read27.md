# GraphQL @connection section

## What is GraphQL?
---

The Amplify CLI provides GraphQL directives to enhance your schema with additional capabilities such as custom indexes, authorization rules, function triggers, and more.


### Annotations

- `@model`: Defines top level object types in your API that are backed by Amazon DynamoDB
- `@key`: Configures custom index structures for @model types
- `@auth`: Defines authorization rules for your @model types and fields
- `@connection`: Defines 1:1, 1:M, and N:M relationships between @model types
- `@function`: Configures a Lambda function resolvers for a field
- `@http`: Configures an HTTP resolver for a field
- `@predictions`: Queries an orchestration of AI/ML services such as Amazon Rekognition, Amazon Translate, and/or Amazon Polly
- `@searchable`: Makes your data searchable by streaming it to Amazon OpenSearch
- `@versioned`: Defines the versioning and conflict resolution strategy for an @model type


### third party directives

- `@algolia`: Add serverless search to your Amplify API with Algolia
- `@ttl`: Enable DynamoDB's time-to-live feature to auto-delete old entries in your AWS Amplify API
- `@firehose`: Add a simple interceptor to all of your Amplify API mutations and queries
- `@retain`: Enable the "Retain" deletion policy for your Amplify-generated DynamoDB tables

## Add relationships between types

---

The @connection directive enables you to specify relationships between @model types. Currently, this supports one-to-one, one-to-many, and many-to-one relationships. You may implement many-to-many relationships using two one-to-many connections and a joining @model type.

`Note`: After you have pushed a @connection directive you should not try to change it. If you try to change it, the DynamoDB UpdateTable operation will fail. Should you need to change a @connection, you should add a new @connection that implements the new access pattern, update your application to use the new @connection, and then delete the old @connection when it's no longer needed.



## Resources/Citations
---

- [GraphQL @connection section](https://docs.amplify.aws/cli-legacy/graphql-transformer/directives/)
