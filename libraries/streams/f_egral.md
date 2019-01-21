---
layout: function
title: egral
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  int append_integral(const cl::sycl::stream &, const int &, bool):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A integral value to be appended to the stream object."
        name: value
        type: const int &
      - description: " Whether to apply stream manipulators when streaming"
        name: useManipulators
        type: bool
    description: Template function that appends a integral value to a stream object.
    return: ""
    signature_with_names: int append_integral(const cl::sycl::stream & os, const int & value, bool useManipulators)
  int append_integral(const cl::sycl::stream &, const unsigned long &, bool):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A integral value to be appended to the stream object."
        name: value
        type: const unsigned long &
      - description: " Whether to apply stream manipulators when streaming"
        name: useManipulators
        type: bool
    description: Template function that appends a integral value to a stream object.
    return: ""
    signature_with_names: int append_integral(const cl::sycl::stream & os, const unsigned long & value, bool useManipulators)
  "template <typename valueT>\nint append_integral(const cl::sycl::stream &, const valueT &, bool)":
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A integral value to be appended to the stream object."
        name: value
        type: const valueT &
      - description: " Whether to apply stream manipulators when streaming"
        name: useManipulators
        type: bool
    description: Template function that appends a integral value to a stream object.
    return: ""
    signature_with_names: "template <typename valueT>\nint append_integral(const cl::sycl::stream & os, const valueT & value, bool useManipulators)"
---
