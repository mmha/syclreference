---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::queue & operator=(cl::sycl::queue &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::queue &&
    description: Completely moves the contents of a queue to that of another queue.
    return: ""
    signature_with_names: cl::sycl::queue & operator=(cl::sycl::queue && rhs)
  cl::sycl::queue & operator=(const cl::sycl::queue &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::queue &
    description: Completely assigns the contents of the queue to that of another queue.
    return: ""
    signature_with_names: cl::sycl::queue & operator=(const cl::sycl::queue & rhs)
---
