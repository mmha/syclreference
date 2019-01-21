---
layout: method
title: h_item<dimensions>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit h_item<dimensions>(const cl::sycl::h_item::base_t &):
    arguments:
      - description: " The base object to copy from"
        name: base
        type: const cl::sycl::h_item::base_t &
    description: Constructs an instance from a base object
    return: ""
    signature_with_names: explicit h_item<dimensions>(const cl::sycl::h_item::base_t & base)
  h_item<dimensions>():
    annotation:
      - delete
    description: Not user constructible
    return: ""
    signature_with_names: h_item<dimensions>()
---
