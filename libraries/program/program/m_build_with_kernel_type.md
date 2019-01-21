---
layout: method
title: build_with_kernel_type
owner: __MISSING__
brief: Build a SYCL kernel using its name and optional custom build options. This function produces a ready-to-run program. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename kernelT>\nvoid build_with_kernel_type(cl::sycl::string_class)":
    arguments:
      - description: " The string specifying the build options to provide to the"
        name: buildOptions
        type: cl::sycl::string_class
    description: Build a SYCL kernel using its name and optional custom build options. This function produces a ready-to-run program. Note that calling this member function is invalid if the program has already been successfully compiled, built or linked via either link(string_class), compile_with_kernel_type(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
    return: ""
    signature_with_names: "template <typename kernelT>\nvoid build_with_kernel_type(cl::sycl::string_class buildOptions)"
---
