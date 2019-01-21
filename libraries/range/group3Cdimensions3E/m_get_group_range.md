---
layout: method
title: get_group_range
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  range<dimensions> get_group_range() const:
    description: the group range for all dimensions
    return: " the value of the group range for each dimension of the group."
    signature_with_names: range<dimensions> get_group_range() const
  size_t get_group_range(unsigned int) const:
    arguments:
      - description: " the dimension of the group range to be returned."
        name: dimension
        type: unsigned int
    description: Returns the group range in a specified dimension.
    return: " the value of the group range in the specified dimension."
    signature_with_names: size_t get_group_range(unsigned int dimension) const
---
