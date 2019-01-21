---
layout: method
title: create_program_for_kernel
owner: __MISSING__
brief: Returns a program for a kernel from a context.
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename kernelT>\nstatic cl::sycl::program create_program_for_kernel(cl::sycl::context)":
    arguments:
      - description: " The context that the kernel is to be created on."
        name: c
        type: cl::sycl::context
    description: Returns a program for a kernel from a context.
    return: " The created program."
    signature_with_names: "template <typename kernelT>\nstatic cl::sycl::program create_program_for_kernel(cl::sycl::context c)"
---
