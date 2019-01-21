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
    description: Retrieves the id representing the position of the item in the global iteration space
    return: " Global ID"
    signature_with_names: id<dimensions> get_global_id() const
  size_t get_global_id(int) const:
    arguments:
      - description: " Which value of the ID to retrieve"
        name: dimension
        type: int
    description: Retrieves the value of the global ID for the specified dimension
    return: " Element of the global ID"
    signature_with_names: size_t get_global_id(int dimension) const
---
