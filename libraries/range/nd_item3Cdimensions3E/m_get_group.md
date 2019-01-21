---
layout: method
title: get_group
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  group<dimensions> get_group() const:
    description: Returns the group.
    return: " A "
    signature_with_names: group<dimensions> get_group() const
  size_t get_group(unsigned int) const:
    arguments:
      - description: ""
        name: dim
        type: unsigned int
    description: Returns the current group id in a given dimension.
    return: " the value of the group range in the specified dimension."
    signature_with_names: size_t get_group(unsigned int dim) const
---
