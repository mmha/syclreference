---
layout: method
title: link
owner: __MISSING__
brief: Link all compiled programs using the (optional) link options. This function produce a ready-to-run program using a compiled program. Note that calling this member function is invalid if the cl_program has already been successfully built or linked via either link(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
tags:
  - method
defined-in-file: ""
overloads:
  void link(cl::sycl::string_class):
    arguments:
      - description: " String specifying the link options to provide to the"
        name: linkOptions
        type: cl::sycl::string_class
    description: Link all compiled programs using the (optional) link options. This function produce a ready-to-run program using a compiled program. Note that calling this member function is invalid if the cl_program has already been successfully built or linked via either link(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
    return: ""
    signature_with_names: void link(cl::sycl::string_class linkOptions)
---
