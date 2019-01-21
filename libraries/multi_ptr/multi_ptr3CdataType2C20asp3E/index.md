---
layout: class
title: multi_ptr<dataType, asp>
owner: __MISSING__
brief: multi_ptr, generic pointer class. This class have the same interface as the explicit pointer classes (global_ptr, private_ptr, local_ptr and constant_ptr). The address space where the data point to is defined by the template parameter Space. A cast operator allow the conversion from a multi_ptr object to its equivalent explicit one.
tags:
  - class
defined-in-file: ""
declaration: "template <typename dataType, cl::sycl::access::address_space asp>\nclass cl::sycl::multi_ptr;"
dtor: unspecified
typedefs:
  const_pointer_t:
    definition: typename multi_ptr_base::const_pointer_t
    description: ""
  const_reference_t:
    definition: const typename multi_ptr_base::asp_type &
    description: Raw reference-to-const definition.
  difference_type:
    definition: typename multi_ptr_base::difference_type
    description: ""
  element_type:
    definition: typename multi_ptr_base::element_type
    description: ""
  pointer_t:
    definition: typename multi_ptr_base::pointer_t
    description: ""
  reference_t:
    definition: typename multi_ptr_base::asp_type &
    description: Raw reference definition.
namespace:
  - cl
  - sycl
---
