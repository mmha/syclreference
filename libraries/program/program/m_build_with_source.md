---
layout: method
title: build_with_source
owner: __MISSING__
brief: Creates and builds a program from OpenCL C kernel source and optional build options. This function produces a ready-to-run program.
tags:
  - method
defined-in-file: ""
overloads:
  void build_with_source(cl::sycl::string_class, cl::sycl::string_class):
    arguments:
      - description: " Source of the OpenCL kernel."
        name: kernelSource
        type: cl::sycl::string_class
      - description: " The string specifying the build options to provide to the"
        name: buildOptions
        type: cl::sycl::string_class
    description: Creates and builds a program from OpenCL C kernel source and optional build options. This function produces a ready-to-run program.
    return: ""
    signature_with_names: void build_with_source(cl::sycl::string_class kernelSource, cl::sycl::string_class buildOptions)
---
