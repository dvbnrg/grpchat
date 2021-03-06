# Chat based on gRPC

Project `grpchat` - simple server/client chat based on gRPC
, Protocol Buffers with golang for server side and Vue, Typescript, gRPC-web, Stylus and Cypress for client side

## Usage:

To begin development:

```
docker-compose up --build
```

## Project:

Project structure:

```
.
├── client/ - vue frontend
├── schema/ - proto files + generated code by protoc
└── server/ - go backend
```

## Todo:

1. Fix bug: after reload page - stream does not closing
2. Add authentication
3. Make better UI for messages and input
4. Add modal for username ask

## Links:

Read about protobuf [here](https://developers.google.com/protocol-buffers/)

What is [gRPC](https://grpc.io)?
