---
layout: function
title: operator!=
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  bool operator!=(const cl::sycl::event &, const cl::sycl::event &):
    arguments:
      - description: " Left-hand-side object in comparison"
        name: lhs
        type: const cl::sycl::event &
      - description: " Right-hand-side object in comparison"
        name: rhs
        type: const cl::sycl::event &
    description: Determines if lhs and rhs are not equal
    return: " True if different underlying objects"
    signature_with_names: bool operator!=(const cl::sycl::event & lhs, const cl::sycl::event & rhs)
---
