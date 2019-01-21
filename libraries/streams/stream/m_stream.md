---
layout: method
title: stream
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  stream(cl::sycl::stream &&):
    annotation:
      - default
    arguments:
      - description: ""
        name: unnamed-0
        type: cl::sycl::stream &&
        unnamed: true
    description: Move constructor
    return: ""
    signature_with_names: stream(cl::sycl::stream &&)
  stream(const cl::sycl::stream &):
    annotation:
      - default
    arguments:
      - description: ""
        name: unnamed-0
        type: const cl::sycl::stream &
        unnamed: true
    description: Copy constructor
    return: ""
    signature_with_names: stream(const cl::sycl::stream &)
  stream(size_t, size_t, cl::sycl::handler &):
    arguments:
      - description: " The size of the stream's buffer."
        name: bufferSize
        type: size_t
      - description: " The maximum size of a single statement in the stream's"
        name: maxStatementSize
        type: size_t
      - description: " A reference to the handler that the stream is to be associated"
        name: cgh
        type: cl::sycl::handler &
    description: Constructor that takes a buffer size, a max statement size and a handler reference and constructs a stream of the buffer size, associated with the provided handler
    return: ""
    signature_with_names: stream(size_t bufferSize, size_t maxStatementSize, cl::sycl::handler & cgh)
---
