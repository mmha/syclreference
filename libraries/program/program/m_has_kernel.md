---
layout: method
title: has_kernel
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  bool has_kernel(cl::sycl::string_class) const:
    arguments:
      - description: ""
        name: kernelName
        type: cl::sycl::string_class
    description: Checks whether the program contains a kernel specified by the name.
    return: " True if the OpenCL C kernel function defined by kernelName is an"
    signature_with_names: bool has_kernel(cl::sycl::string_class kernelName) const
  "template <typename kernelT>\nbool has_kernel() const":
    description: Checks whether the program contains a kernel specified by the type.
    return: " True if the SYCL kernel function defined by the type kernelT"
    signature_with_names: "template <typename kernelT>\nbool has_kernel() const"
---
