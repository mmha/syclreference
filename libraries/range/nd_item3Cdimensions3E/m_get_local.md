---
layout: method
title: get_local
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  id<dimensions> get_local() const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_local with nd_item::get_local_id.)
    description: Return the local id for all dimension.
    return: " An "
    signature_with_names: id<dimensions> get_local() const
  size_t get_local(unsigned int) const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_local with nd_item::get_local_id.)
    arguments:
      - description: " of local id to return. Must be in the range [0,2]."
        name: dimension
        type: unsigned int
    description: Returns the local id for a specific dimension.
    return: " the local id for the specified dimension."
    signature_with_names: size_t get_local(unsigned int dimension) const
---
