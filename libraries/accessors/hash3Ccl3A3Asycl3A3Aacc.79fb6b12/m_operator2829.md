---
layout: method
title: operator()
owner: __MISSING__
brief: enables calling an std::hash object as a function with the object to be hashed as a parameter
tags:
  - method
defined-in-file: ""
overloads:
  std::size_t operator()(const cl::sycl::accessor<elemT, kDims, kMode, kTarget, isPlaceholder> &) const:
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::accessor<elemT, kDims, kMode, kTarget, isPlaceholder> &
    description: enables calling an std::hash object as a function with the object to be hashed as a parameter
    return: ""
    signature_with_names: std::size_t operator()(const cl::sycl::accessor<elemT, kDims, kMode, kTarget, isPlaceholder> & rhs) const
---
