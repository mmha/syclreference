---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::device & operator=(cl::sycl::device &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::device &&
    description: Completely moves the contents of the device to that of another.
    return: ""
    signature_with_names: cl::sycl::device & operator=(cl::sycl::device && rhs)
  cl::sycl::device & operator=(const cl::sycl::device &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::device &
    description: Completely assigns the contents of the device to that of another and retains the cl_device_id object if the device is not in host mode.
    return: ""
    signature_with_names: cl::sycl::device & operator=(const cl::sycl::device & rhs)
---
