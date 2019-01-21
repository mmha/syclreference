---
layout: method
title: get
owner: __MISSING__
brief: If value is negative, display the minus sign and return the absolute value
tags:
  - method
defined-in-file: ""
overloads:
  static valueT get(const cl::sycl::stream &, valueT):
    arguments:
      - description: " The stream object"
        name: os
        type: const cl::sycl::stream &
      - description: " Input value"
        name: value
        type: valueT
    description: If value is negative, display the minus sign and return the absolute value
    return: " Absolute value"
    signature_with_names: static valueT get(const cl::sycl::stream & os, valueT value)
---
