---
layout: function
title: operator==
owner: __MISSING__
brief: Determines if lhs and rhs are equal
tags:
  - function
defined-in-file: ""
overloads:
  bool operator==(const cl::sycl::program &, const cl::sycl::program &):
    arguments:
      - description: " Left-hand-side object in comparison"
        name: lhs
        type: const cl::sycl::program &
      - description: " Right-hand-side object in comparison"
        name: rhs
        type: const cl::sycl::program &
    description: Determines if lhs and rhs are equal
    return: " True if same underlying object"
    signature_with_names: bool operator==(const cl::sycl::program & lhs, const cl::sycl::program & rhs)
---
