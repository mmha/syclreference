---
layout: method
title: operator()
owner: __MISSING__
brief: enables calling an std::hash object as a function with the object to be hashed as a parameter
tags:
  - method
defined-in-file: ""
overloads:
  std::size_t operator()(const cl::sycl::buffer<T, dimensions, AllocatorT> &) const:
    arguments:
      - description: " the object to be hashed"
        name: object
        type: const cl::sycl::buffer<T, dimensions, AllocatorT> &
    description: enables calling an std::hash object as a function with the object to be hashed as a parameter
    return: ""
    signature_with_names: std::size_t operator()(const cl::sycl::buffer<T, dimensions, AllocatorT> & object) const
---
