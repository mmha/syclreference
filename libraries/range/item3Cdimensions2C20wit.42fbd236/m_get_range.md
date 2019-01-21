---
layout: method
title: get_range
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  range<dimensions> get_range() const:
    description: Get the global range of the enqueued kernel if provided by a handler::parallel_for. Get the local range if used if provided by a
    return: " the values of the global range for all dimensions."
    signature_with_names: range<dimensions> get_range() const
  size_t get_range(int) const:
    arguments:
      - description: " The dimension of the range to retrieve."
        name: dimension
        type: int
    description: Gets the global range in a specified dimension if provided by a handler::parallel_for and gets the local range in a specified dimension if provided by a
    return: " The value of the global range in the dimension specified."
    signature_with_names: size_t get_range(int dimension) const
---
