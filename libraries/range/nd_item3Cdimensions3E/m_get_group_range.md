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
    description: Returns the group range of the enqueued nd_range.
    return: " the value of the group range for all dimensions."
    signature_with_names: range<dimensions> get_group_range() const
  size_t get_group_range(int) const:
    arguments:
      - description: " of the range to be returned. Must be in the range [0,2]"
        name: dimension
        type: int
    description: Returns the group range of the enqueued nd_range for a specific dimension.
    return: " the value of the group range for all dimensions."
    signature_with_names: size_t get_group_range(int dimension) const
---
