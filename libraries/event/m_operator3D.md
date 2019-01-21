---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::event & operator=(cl::sycl::event &&):
    arguments:
      - description: " will have its contents moved. after the operation rhs will be"
        name: rhs
        type: cl::sycl::event &&
    description: Default move assignment operator
    return: ""
    signature_with_names: cl::sycl::event & operator=(cl::sycl::event && rhs)
  cl::sycl::event & operator=(const cl::sycl::event &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::event &
    description: Default copy assignment.
    return: ""
    signature_with_names: cl::sycl::event & operator=(const cl::sycl::event & rhs)
---
