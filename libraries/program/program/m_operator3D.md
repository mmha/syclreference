---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::program & operator=(cl::sycl::program &&):
    arguments:
      - description: " The program being assigned from."
        name: rhs
        type: cl::sycl::program &&
    description: Assignment operator that initialises a copy of the program with the same underlying cl_program, associated context and list of associated devices.
    return: ""
    signature_with_names: cl::sycl::program & operator=(cl::sycl::program && rhs)
  cl::sycl::program & operator=(const cl::sycl::program &):
    arguments:
      - description: " The program being assigned from."
        name: rhs
        type: const cl::sycl::program &
    description: Assignment operator that initialises a copy of the program with the same underlying cl_program, associated context and list of associated devices.
    return: ""
    signature_with_names: cl::sycl::program & operator=(const cl::sycl::program & rhs)
---
