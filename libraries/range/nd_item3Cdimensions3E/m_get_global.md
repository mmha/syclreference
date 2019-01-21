---
layout: method
title: get_global
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get_global() const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_global with nd_item::get_global_id.)
    description: Return the global id for all dimension.
    return: " An "
    signature_with_names: id<dimensions> get_global() const
  size_t get_global(unsigned int) const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_global with nd_item::get_global_id.)
    arguments:
      - description: " of global id to return. Must be in the range [0,2]."
        name: dimension
        type: unsigned int
    description: Returns the global id for a specific dimension.
    return: " the global id for the specified dimension."
    signature_with_names: size_t get_global(unsigned int dimension) const
---
