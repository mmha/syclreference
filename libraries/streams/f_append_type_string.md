---
layout: function
title: append_type_string
owner: __MISSING__
brief: Appends a string representation of a type to the stream
tags:
  - function
defined-in-file: ""
overloads:
  void append_type_string(const cl::sycl::stream &, char *, int, int):
    arguments:
      - description: " Stream object to append to"
        name: os
        type: const cl::sycl::stream &
      - description: " String representing the type name."
        name: typeStr
        type: char *
      - description: " Number of characters in the provided type string"
        name: numChars
        type: int
      - description: " Optional number of dimensions of the type"
        name: dimensions
        type: int
    description: Appends a string representation of a type to the stream
    return: ""
    signature_with_names: void append_type_string(const cl::sycl::stream & os, char * typeStr, int numChars, int dimensions)
---
