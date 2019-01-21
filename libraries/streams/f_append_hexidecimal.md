---
layout: function
title: append_hexidecimal
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename valueT>\nvoid append_hexidecimal(const cl::sycl::stream &, const valueT &)":
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A hexadecimal value to be appended to the stream object."
        name: value
        type: const valueT &
    description: Template function that appends a hexadecimal value to a stream object.
    return: ""
    signature_with_names: "template <typename valueT>\nvoid append_hexidecimal(const cl::sycl::stream & os, const valueT & value)"
  void append_hexidecimal(const cl::sycl::stream &, const int &):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A hexadecimal value to be appended to the stream object."
        name: value
        type: const int &
    description: Template function that appends a hexadecimal value to a stream object.
    return: ""
    signature_with_names: void append_hexidecimal(const cl::sycl::stream & os, const int & value)
  void append_hexidecimal(const cl::sycl::stream &, const long &):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A hexadecimal value to be appended to the stream object."
        name: value
        type: const long &
    description: Template function that appends a hexadecimal value to a stream object.
    return: ""
    signature_with_names: void append_hexidecimal(const cl::sycl::stream & os, const long & value)
  void append_hexidecimal(const cl::sycl::stream &, const unsigned long &):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A hexadecimal value to be appended to the stream object."
        name: value
        type: const unsigned long &
    description: Template function that appends a hexadecimal value to a stream object.
    return: ""
    signature_with_names: void append_hexidecimal(const cl::sycl::stream & os, const unsigned long & value)
---
