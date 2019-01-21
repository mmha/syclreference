---
layout: method
title: operator()
owner: __MISSING__
brief: Inline function call operator that streams part of the vec to a stream object. This function call operator streams the x and y elements of the vec object.
tags:
  - method
defined-in-file: ""
overloads:
  const cl::sycl::stream & operator()(const cl::sycl::stream &, const vec<elementT, kDimensions> &):
    arguments:
      - description: " A reference to the stream object."
        name: os
        type: const cl::sycl::stream &
      - description: " A reference to the vec object."
        name: rhs
        type: const vec<elementT, kDimensions> &
    description: Inline function call operator that streams part of the vec to a stream object. This function call operator streams the x and y elements of the vec object.
    return: " A reference to the stream object."
    signature_with_names: const cl::sycl::stream & operator()(const cl::sycl::stream & os, const vec<elementT, kDimensions> & rhs)
---
