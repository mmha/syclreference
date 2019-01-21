---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::context & operator=(cl::sycl::context &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::context &&
    description: Completely moves the contents of the context to that of another.
    return: ""
    signature_with_names: cl::sycl::context & operator=(cl::sycl::context && rhs)
  cl::sycl::context & operator=(const cl::sycl::context &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::context &
    description: Completely assigns the contents of the context to that of another and retains the cl_context object if the context is not in host mode.
    return: ""
    signature_with_names: cl::sycl::context & operator=(const cl::sycl::context & rhs)
---
