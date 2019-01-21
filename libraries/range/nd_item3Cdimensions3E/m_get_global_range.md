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
    description: Get the global range of the enqueued nd_range.
    return: " the values of the global range for all dimensions."
    signature_with_names: range<dimensions> get_global_range() const
  size_t get_global_range(int) const:
    arguments:
      - description: " of the global range to be returned. Must be in the range"
        name: dimension
        type: int
    description: Get the global range for a specified dimension.
    return: " the value of the global range for the specified dimension."
    signature_with_names: size_t get_global_range(int dimension) const
---
