## Introduction

The de-facto standard of microservice communications today is JSON/REST,
but many companies and open source projects are adopting
[gRPC](https://grpc.io/) for greenfield projects as well as existing
architectures. It offers type safe, high performance RPC for polyglot
environments. However, it does not on its own integrate well into existing
JSON/REST architectures. Fortunately, that is what the
[gRPC-Gateway project](https://github.com/grpc-ecosystem/grpc-gateway/) allows
us to do. After my talk you will be able to write your own gRPC service and
expose it behind a JSON/REST interface.

## Structure

I will spend the first 10 or so minutes laying the technical ground for the talk
by talking about JSON/REST, giving a quick intro into gRPC and
[protocol buffers](https://developers.google.com/protocol-buffers/), then
introducing the gRPC-Gateway as a way to integrate gRPC into existing
architectures with strict JSON/REST interface requirements.

I will then move on to a live demo showing the power of this workflow by
iterating on a simple design. The audience will be able to follow along on their
own by cloning the
[boilerplate repository](https://github.com/johanbrandhorst/grpc-gateway-boilerplate)
.

I will gradually introduce more complicated topics like PATCH requests,
middleware, authentication, working with browser clients, cookies, websockets
and more.

I will leave some time at the end for any questions.

## Take away

The audience will have learned about protocol buffers and gRPC, and why they
offer a compelling alternative to JSON/REST. They will know how to create a
gRPC server with both a gRPC and a JSON/REST interface.

## Target audience

- Developers with some experience writing services that expose JSON/REST
  interfaces.

- Developers who have heard about gRPC and are curious to try it, but can't
  readily use gRPC because of strict JSON/REST interface requirements.

- Developers who want to develop a gRPC backend to a browser application, but
  aren't able to use gRPC-Web in the frontend.

- Developers who want to migrate their architecture from JSON/REST to gRPC, one
  service at a time.
