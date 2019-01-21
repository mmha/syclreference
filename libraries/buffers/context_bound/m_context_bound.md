---
layout: method
title: context_bound
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  context_bound(cl::sycl::property::buffer::context_bound &&):
    arguments:
      - description: ""
        name: unnamed-0
        type: cl::sycl::property::buffer::context_bound &&
        unnamed: true
    description: ""
    return: ""
    signature_with_names: context_bound(cl::sycl::property::buffer::context_bound &&)
  context_bound(const cl::sycl::context &):
    arguments:
      - description: " Context to be bound to the buffer."
        name: boundContext
        type: const cl::sycl::context &
    description: Constructs a SYCL context_bound property instance with a copy of a SYCL context.
    return: ""
    signature_with_names: context_bound(const cl::sycl::context & boundContext)
  context_bound(const cl::sycl::property::buffer::context_bound &):
    arguments:
      - description: ""
        name: unnamed-0
        type: const cl::sycl::property::buffer::context_bound &
        unnamed: true
    description: ""
    return: ""
    signature_with_names: context_bound(const cl::sycl::property::buffer::context_bound &)
---
