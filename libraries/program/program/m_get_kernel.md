---
layout: method
title: get_kernel
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::kernel get_kernel(cl::sycl::string_class) const:
    arguments:
      - description: " The string specifying the kernel name."
        name: kernelName
        type: cl::sycl::string_class
    description: Retrieve a SYCL
    return: " The kernel that has been created form the kernel name parameter."
    signature_with_names: cl::sycl::kernel get_kernel(cl::sycl::string_class kernelName) const
  "template <typename kernelT>\ncl::sycl::kernel get_kernel() const":
    description: Retrieve a SYCL
    return: " The kernel that has been created from the kernel name parameter."
    signature_with_names: "template <typename kernelT>\ncl::sycl::kernel get_kernel() const"
---
