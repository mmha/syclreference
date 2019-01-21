---
layout: function
title: append_floating_point
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename valueT>\nvoid append_floating_point(const cl::sycl::stream &, const valueT &)":
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A floating point value to be appended to the stream object."
        name: value
        type: const valueT &
    description: Template function that appends a floating point value to a stream object.
    return: ""
    signature_with_names: "template <typename valueT>\nvoid append_floating_point(const cl::sycl::stream & os, const valueT & value)"
  void append_floating_point(const cl::sycl::stream &, const double &):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A floating point value to be appended to the stream object."
        name: value
        type: const double &
    description: Template function that appends a floating point value to a stream object.
    return: ""
    signature_with_names: void append_floating_point(const cl::sycl::stream & os, const double & value)
  void append_floating_point(const cl::sycl::stream &, const float &):
    arguments:
      - description: " The stream object to be appended to."
        name: os
        type: const cl::sycl::stream &
      - description: " A floating point value to be appended to the stream object."
        name: value
        type: const float &
    description: Template function that appends a floating point value to a stream object.
    return: ""
    signature_with_names: void append_floating_point(const cl::sycl::stream & os, const float & value)
---
