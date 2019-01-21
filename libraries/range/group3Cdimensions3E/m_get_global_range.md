---
layout: method
title: get_global_range
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  range<dimensions> get_global_range() const:
    description: Get the global range for all dimensions
    return: " the value of the global range for each dimension of the nd_range."
    signature_with_names: range<dimensions> get_global_range() const
  size_t get_global_range(unsigned int) const:
    arguments:
      - description: " the dimension of the global range to be returned."
        name: dimension
        type: unsigned int
    description: Returns the global range in a specified dimension.
    return: " the value of the global range in the specified dimension."
    signature_with_names: size_t get_global_range(unsigned int dimension) const
---
