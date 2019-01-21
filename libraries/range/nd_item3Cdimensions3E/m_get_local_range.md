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
    description: Get the local range of the enqueued nd_range.
    return: " the values of the local range for all dimensions."
    signature_with_names: range<dimensions> get_local_range() const
  size_t get_local_range(int) const:
    arguments:
      - description: " of the local range to be returned. Must be in the range"
        name: dimension
        type: int
    description: Get the local range for a specified dimension.
    return: " the value of the local range for the specified dimension."
    signature_with_names: size_t get_local_range(int dimension) const
---
