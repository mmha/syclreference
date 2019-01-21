---
layout: function
title: append_index_array
owner: __MISSING__
brief: Appends an index_array object to the stream
tags:
  - function
defined-in-file: ""
overloads:
  void append_index_array(const cl::sycl::stream &, const detail::index_array &, int):
    arguments:
      - description: " Stream object to append to"
        name: os
        type: const cl::sycl::stream &
      - description: " Array of indexes"
        name: value
        type: const detail::index_array &
      - description: " Number of elements of the index array"
        name: numElements
        type: int
    description: Appends an index_array object to the stream
    return: ""
    signature_with_names: void append_index_array(const cl::sycl::stream & os, const detail::index_array & value, int numElements)
---
