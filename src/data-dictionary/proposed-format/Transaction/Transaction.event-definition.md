---
name: Transaction
type: event
dataSources:
  - APM
attributes:
  - AwsLambdaInvocation/request.headers.contentLength
  - AwsLambdaInvocation/request.headers.contentType
  - Span/trace.id
---

A transaction is a logical unit of work in a software application, such as HTTP requests, SQL queries, background processes, message queue activity, etc. The Transaction event includes information about the app, database calls, the duration of the transaction, and any errors that may occur.