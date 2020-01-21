# grpc_getting_started

## Overview
Getting started with grpc (in C++).

Building with bazel.

## Building and Running the Code
To only build the server and client, run the following:
```
bazel build :greeter_server
bazel build :greeter_client
```

To build and run the server and client, run the following:
```
bazel run :greeter_server
bazel run :greeter_client
```
