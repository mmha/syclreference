---
layout: class
title: exception_list
owner: __MISSING__
brief: List of exceptions thrown asynchronously, contains objects of type exception_ptr_class.
tags:
  - class
defined-in-file: ""
declaration: "\nclass cl::sycl::exception_list;"
dtor: unspecified
typedefs:
  const_iterator:
    definition: _exception_list::const_iterator
    description: Constant iterator definition
  const_reference:
    definition: const cl::sycl::exception_list::value_type &
    description: Constant reference type to a list element
  iterator:
    definition: _exception_list::iterator
    description: iterator definition
  reference:
    definition: cl::sycl::exception_list::value_type &
    description: Reference type to a list element
  size_type:
    definition: std::size_t
    description: Type of the size of the list
  value_type:
    definition: cl::sycl::exception_ptr_class
    description: Type of the list elements
namespace:
  - cl
  - sycl
---
