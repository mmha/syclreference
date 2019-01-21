---
layout: method
title: get
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get() const:
    annotation:
      - deprecated (get() was deprecated in SYCL 1.2.1)
    description: Get Group ID
    return: " the group id for all dimensions of the nd_range"
    signature_with_names: id<dimensions> get() const
  size_t get(unsigned int) const:
    annotation:
      - deprecated (get(unsigned) was deprecated in SYCL 1.2.1)
    arguments:
      - description: ""
        name: dimension
        type: unsigned int
    description: Get Group ID
    return: " the group id for that dimension"
    signature_with_names: size_t get(unsigned int dimension) const
---
