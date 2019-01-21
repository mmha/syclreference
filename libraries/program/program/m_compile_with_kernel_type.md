---
layout: method
title: compile_with_kernel_type
owner: __MISSING__
brief: Compile a SYCL kernel using his name and optional custom compile options. This function produce a ready to link program. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename kernelT>\nvoid compile_with_kernel_type(cl::sycl::string_class)":
    arguments:
      - description: " The string specifying the compile options that will be"
        name: compileOptions
        type: cl::sycl::string_class
    description: Compile a SYCL kernel using his name and optional custom compile options. This function produce a ready to link program. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
    return: ""
    signature_with_names: "template <typename kernelT>\nvoid compile_with_kernel_type(cl::sycl::string_class compileOptions)"
---
