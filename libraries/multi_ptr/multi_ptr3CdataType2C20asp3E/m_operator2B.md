---
layout: method
title: operator+
owner: __MISSING__
brief: Creates a new multi_ptr that points r forward compared to *this
tags:
  - method
defined-in-file: ""
overloads:
  multi_ptr<dataT, addressSpace> operator+(cl::sycl::multi_ptr::difference_type) const:
    arguments:
      - description: " Number of elements to increment the underlying pointer by"
        name: r
        type: cl::sycl::multi_ptr::difference_type
    description: Creates a new multi_ptr that points r forward compared to *this
    return: " New multi_ptr object with the pointer advanced by r"
    signature_with_names: multi_ptr<dataT, addressSpace> operator+(cl::sycl::multi_ptr::difference_type r) const
---
