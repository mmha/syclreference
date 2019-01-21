---
layout: method
title: get_global_id
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get_global_id() const:
    description: Return the global id for all dimension.
    return: " An "
    signature_with_names: id<dimensions> get_global_id() const
  size_t get_global_id(unsigned int) const:
    arguments:
      - description: " of global id to return. Must be in the range [0,2]."
        name: dimension
        type: unsigned int
    description: Returns the global id for a specific dimension.
    return: " the global id for the specified dimension."
    signature_with_names: size_t get_global_id(unsigned int dimension) const
---
