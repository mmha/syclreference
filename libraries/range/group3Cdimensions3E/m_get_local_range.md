---
layout: method
title: get_local_range
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  range<dimensions> get_local_range() const:
    description: Get the local range for all dimensions
    return: " the value of the local range for each dimension of the nd_range."
    signature_with_names: range<dimensions> get_local_range() const
  size_t get_local_range(unsigned int) const:
    arguments:
      - description: " the dimension of the local range to be returned."
        name: dimension
        type: unsigned int
    description: Returns the local range in a specified dimension.
    return: " the value of the local range in the specified dimension."
    signature_with_names: size_t get_local_range(unsigned int dimension) const
---
