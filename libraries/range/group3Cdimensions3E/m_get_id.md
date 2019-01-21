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
    description: Get Group ID
    return: " the group id for all dimensions of the nd_range"
    signature_with_names: id<dimensions> get_id() const
  size_t get_id(unsigned int) const:
    arguments:
      - description: ""
        name: dimension
        type: unsigned int
    description: Get Group ID
    return: " the group id for that dimension"
    signature_with_names: size_t get_id(unsigned int dimension) const
---
