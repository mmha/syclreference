---
layout: method
title: half
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  half():
    description: default constructor, inits as zero
    return: ""
    signature_with_names: half()
  half(cl::sycl::half &&):
    arguments:
      - description: ""
        name: unnamed-0
        type: cl::sycl::half &&
        unnamed: true
    description: ""
    return: ""
    signature_with_names: half(cl::sycl::half &&)
  half(const cl::sycl::half &):
    arguments:
      - description: ""
        name: unnamed-0
        type: const cl::sycl::half &
        unnamed: true
    description: ""
    return: ""
    signature_with_names: half(const cl::sycl::half &)
  half(const float &):
    arguments:
      - description: " the float to be converted to 16 bits"
        name: f
        type: const float &
    description: Takes in a 32 bit float and converts it to 16 bits
    return: ""
    signature_with_names: half(const float & f)
---
