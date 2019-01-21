---
layout: method
title: program
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit program(const cl::sycl::context &):
    arguments:
      - description: " A reference to the context that the cl_program will be"
        name: context
        type: const cl::sycl::context &
    description: Constructor that takes a context. Initialises the cl_program to nullptr.
    return: ""
    signature_with_names: explicit program(const cl::sycl::context & context)
  program(cl::sycl::program &&):
    arguments:
      - description: " The program being copied from."
        name: rhs
        type: cl::sycl::program &&
    description: Copy constructor that initialises a copy of the program with the same underlying cl_program, associated context and list of associated devices.
    return: ""
    signature_with_names: program(cl::sycl::program && rhs)
  program(const cl::sycl::context &, cl_program):
    arguments:
      - description: " A reference to the context that the cl_program will be"
        name: context
        type: const cl::sycl::context &
      - description: " The cl_program that the program will be assigned to."
        name: clProgram
        type: cl_program
    description: Inter-op constructor that takes a context and a cl_program. Note that the clProgram param must have previously been created from the underlying cl_context of the context parameter and the underlying cl_devices from the list of devices parameter.
    return: ""
    signature_with_names: program(const cl::sycl::context & context, cl_program clProgram)
  program(const cl::sycl::context &, vector_class<cl::sycl::device>):
    arguments:
      - description: ""
        name: context
        type: const cl::sycl::context &
      - description: " A list of devices that the program will be associated with."
        name: deviceList
        type: vector_class<cl::sycl::device>
    description: Constructor that takes a context and a list of devices. Initialises the cl_program to nullptr.
    return: ""
    signature_with_names: program(const cl::sycl::context & context, vector_class<cl::sycl::device> deviceList)
  program(const cl::sycl::program &):
    arguments:
      - description: " The program being copied from."
        name: rhs
        type: const cl::sycl::program &
    description: Copy constructor that initialises a copy of the program with the same underlying cl_program, associated context and list of associated devices.
    return: ""
    signature_with_names: program(const cl::sycl::program & rhs)
  program(vector_class<cl::sycl::program>, cl::sycl::string_class):
    arguments:
      - description: " The list programs that the cl_program will be constructed"
        name: programList
        type: vector_class<cl::sycl::program>
      - description: " The string specifying the link options the cl_program will"
        name: linkOptions
        type: cl::sycl::string_class
    description: Linker constructor that takes a list of programs and a string specifying link options. Note that calling this constructor is invalid if the cl_program has already been successfully built or linked via either link(string_class), build_with_kernel_type(string_class) or program(vector_class<program>, string_class).
    return: ""
    signature_with_names: program(vector_class<cl::sycl::program> programList, cl::sycl::string_class linkOptions)
---
