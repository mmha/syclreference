---
layout: method
title: get_id
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get_id() const:
    description: Get the id associated with this item for all dimensions.
    return: " The global "
    signature_with_names: id<dimensions> get_id() const
  size_t get_id(int) const:
    arguments:
      - description: " of the id, in the range [0,2]"
        name: dimension
        type: int
    description: Get the id for a specific dimension.
    return: " the id for the specified dimension."
    signature_with_names: size_t get_id(int dimension) const
---
