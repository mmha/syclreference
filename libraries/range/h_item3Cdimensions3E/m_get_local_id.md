---
layout: method
title: get_local_id
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get_local_id() const:
    description: Retrieves the id representing the position of the item in the logical local iteration space
    return: " Global ID"
    signature_with_names: id<dimensions> get_local_id() const
  size_t get_local_id(int) const:
    arguments:
      - description: " Which value of the ID to retrieve"
        name: dimension
        type: int
    description: Retrieves the value of the logical local ID for the specified dimension
    return: " Element of the logical local ID"
    signature_with_names: size_t get_local_id(int dimension) const
---
