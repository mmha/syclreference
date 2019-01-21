---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::kernel & operator=(cl::sycl::kernel &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::kernel &&
    description: Move assignment operator. Assign a copy of a kernel.
    return: ""
    signature_with_names: cl::sycl::kernel & operator=(cl::sycl::kernel && rhs)
  cl::sycl::kernel & operator=(const cl::sycl::kernel &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::kernel &
    description: Assignment operator. Assign a copy of a kernel.
    return: ""
    signature_with_names: cl::sycl::kernel & operator=(const cl::sycl::kernel & rhs)
---
