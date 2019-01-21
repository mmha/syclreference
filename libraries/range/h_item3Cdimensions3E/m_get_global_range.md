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
    description: Retrieves the range representing the sizes of the global iteration space
    return: " Global range"
    signature_with_names: range<dimensions> get_global_range() const
  size_t get_global_range(int) const:
    arguments:
      - description: " Which value of the range to retrieve"
        name: dimension
        type: int
    description: Retrieves the value of the global range for the specified dimension
    return: " Element of the global range"
    signature_with_names: size_t get_global_range(int dimension) const
---
