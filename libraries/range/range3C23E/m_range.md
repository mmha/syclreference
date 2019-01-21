---
layout: method
title: range
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit range(const detail::index_array_operators<2, cl::sycl::range> &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array_operators<2, cl::sycl::range> &
    description: COMPUTECPP_DEV
    return: ""
    signature_with_names: explicit range(const detail::index_array_operators<2, cl::sycl::range> & indexArray)
  range():
    description: Default constructor. Initialize the range to 1. Equivalent to range<2>(1, 1)
    return: ""
    signature_with_names: range()
  range(const cl::sycl::range<2> &):
    annotation:
      - default
    arguments:
      - description: " The range to copy"
        name: rhs
        type: const cl::sycl::range<2> &
    description: Create a copy of a range.
    return: ""
    signature_with_names: range(const cl::sycl::range<2> & rhs)
  range(const detail::index_array &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array &
    description: ""
    return: ""
    signature_with_names: range(const detail::index_array & indexArray)
  range(size_t, size_t):
    arguments:
      - description: " The size of the first dimension."
        name: dim1
        type: size_t
      - description: " The size of the second dimension."
        name: dim2
        type: size_t
    description: Create a 2 dimension range initialized to dim1 for the first dimension and dim2 for the second.
    return: ""
    signature_with_names: range(size_t dim1, size_t dim2)
---
