---
layout: method
title: operator[]
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::multi_ptr::original_type_cref operator[](size_t) const:
    annotation:
      - deprecated (No operator[] for multi_ptr in SYCL 1.2.1)
    arguments:
      - description: " Index."
        name: i
        type: size_t
    description: operator[], for const object
    return: " Const reference to the i-th element the object points to."
    signature_with_names: cl::sycl::multi_ptr::original_type_cref operator[](size_t i) const
  cl::sycl::multi_ptr::original_type_ref operator[](size_t):
    annotation:
      - deprecated (No operator[] for multi_ptr in SYCL 1.2.1)
    arguments:
      - description: " Index."
        name: i
        type: size_t
    description: operator[]
    return: " Reference to the i-th element the object points to."
    signature_with_names: cl::sycl::multi_ptr::original_type_ref operator[](size_t i)
---
