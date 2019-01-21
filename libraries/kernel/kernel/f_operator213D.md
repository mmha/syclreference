---
layout: function
title: operator!=
owner: __MISSING__
brief: Determines if lhs and rhs are not equal
tags:
  - function
defined-in-file: ""
overloads:
  bool operator!=(const cl::sycl::kernel &, const cl::sycl::kernel &):
    arguments:
      - description: " Left-hand-side object in comparison"
        name: lhs
        type: const cl::sycl::kernel &
      - description: " Right-hand-side object in comparison"
        name: rhs
        type: const cl::sycl::kernel &
    description: Determines if lhs and rhs are not equal
    return: " True if different underlying objects"
    signature_with_names: bool operator!=(const cl::sycl::kernel & lhs, const cl::sycl::kernel & rhs)
---
