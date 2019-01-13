## Introduction

gRPC-Web is a new protocol that allows frontend applications to exchange
information with gRPC backends, allowing type safe, performant and polyglot
interfaces between the frontend and backend.

GopherJS is a mature Go-to-JS transpiler, supporting most of the standard
library and allowing users to wrap arbitrary JS code with type safe Go packages.

In this talk I will introduce the technology and walk the user through the
creation and iteration of a simple GopherJS frontend application, supported by
a gRPC-Go backend.

## Structure

I will spend the first 10 minutes or so of the talk introducing Protobuf, gRPC,
gRPC-Web, GopherJS and my GopherJS gRPC-Web bindings.

I will then create a simple gRPC-Web app from my
[boilerplate base repo](https://github.com/johanbrandhorst/grpcweb-boilerplate/)
, walking the user through the steps of adding, refining and iterating on the
interface. I will introduce and demo the different streaming modes of gRPC.

I will leave some time at the end for questions.

## Take away

The audience will know how they can implement their own GopherJS application
leveraging a gRPC backend via gRPC-Web.

## Target audience

- Developers who are curious about GopherJS but don't know how to get started.

- Developers who are curious about gRPC-Web but don't want to write JavaScript.

- Developers who want to write applications using Go on the frontend and
  the backend.
