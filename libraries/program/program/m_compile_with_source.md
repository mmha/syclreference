---
layout: method
title: compile_with_source
owner: __MISSING__
brief: Compiles a program from the given OpenCL C kernel source. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
tags:
  - method
defined-in-file: ""
overloads:
  void compile_with_source(cl::sycl::string_class, cl::sycl::string_class):
    arguments:
      - description: " to compile"
        name: kernelSource
        type: cl::sycl::string_class
      - description: ""
        name: compileOptions
        type: cl::sycl::string_class
    description: Compiles a program from the given OpenCL C kernel source. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
    return: ""
    signature_with_names: void compile_with_source(cl::sycl::string_class kernelSource, cl::sycl::string_class compileOptions)
---
