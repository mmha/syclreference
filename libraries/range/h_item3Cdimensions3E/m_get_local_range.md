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
    description: Retrieves the range representing the sizes of the logical local iteration space
    return: " Global range"
    signature_with_names: range<dimensions> get_local_range() const
  size_t get_local_range(int) const:
    arguments:
      - description: " Which value of the range to retrieve"
        name: dimension
        type: int
    description: Retrieves the value of the logical local range for the specified dimension
    return: " Element of the logical local range"
    signature_with_names: size_t get_local_range(int dimension) const
---
