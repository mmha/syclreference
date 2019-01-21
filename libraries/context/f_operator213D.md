---
layout: function
title: operator!=
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  bool operator!=(const cl::sycl::context &, const cl::sycl::context &):
    arguments:
      - description: " Left-hand-side object in comparison"
        name: lhs
        type: const cl::sycl::context &
      - description: " Right-hand-side object in comparison"
        name: rhs
        type: const cl::sycl::context &
    description: Determines if lhs and rhs are not equal
    return: " True if different underlying objects"
    signature_with_names: bool operator!=(const cl::sycl::context & lhs, const cl::sycl::context & rhs)
---
