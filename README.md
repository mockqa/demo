# Examples for mock.qa gRPC mocking service
## [Greeter](https://github.com/mockqa/demo/tree/main/examples/greeter)

Greeter example describes a matching for simple cases and unary calls

Scenarios:
* Basic: unary call
* Matching: a message property
* Matching: any message
* Templating: a message property
* Templating: a status code and status detail

## [Counter](https://github.com/mockqa/demo/tree/main/examples/counter)

The counter example shows how to work with unary (non-streaming), client streaming and server streaming gRPC methods

Scenarios:
* Basic: unary call
* Basic: client streaming call
* Basic: server streaming call
* Templating: a message property

## [Credentials](https://github.com/mockqa/demo/tree/main/examples/credentials)

The example shows how to work with credentials and match a request for a particular user using a basic auth

Scenarios:
* Basic: unary call
* Credentials: IP white list
* Credentials: Basic auth
* Credentials: a channel and a call blended config
* Matching: using a wildcard

## [Round-Robin](https://github.com/mockqa/demo/tree/main/examples/round-robin)

The example shows how to implement a round-robin behavior using scenarios and states

Scenarios:
* Basic: unary call
* Matching: scenarios and states
* Templating: a message property

## New demos will be added soon

We are planning to publish new demos that cover all scenarios in the near future, please get back later.

## The list of all demo scenarios
* Basic: unary call
* Basic: client streaming call
* Basic: server streaming call
* Basic: server streaming from a file
* Credentials: IP white list
* Credentials: Basic auth
* Credentials: Certificate
* Credentials: JWT Token
* Credentials: a channel and a call blended config
* Matching: any message
* Matching: a request header
* Matching: a complex message
* Matching: a message property
* Matching: using a wildcard
* Matching: an element inside a nested array
* Matching: a message to a file
* Matching: a message property to a file
* Matching: scenarios and states
* Templating: random data generation
* Templating: a message property
* Templating: a complex message
* Templating: a request header and a request trailer
* Templating: a status code and status detail
* Templating: from a file

## See also
* [C# gRPC Examples](https://github.com/grpc/grpc-dotnet/tree/master/examples)
