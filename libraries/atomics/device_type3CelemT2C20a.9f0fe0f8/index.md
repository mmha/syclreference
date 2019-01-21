---
layout: class
title: device_type<elemT, addressSpace>
owner: __MISSING__
brief: ""
tags:
  - class
defined-in-file: ""
declaration: "template <typename elemT, access::address_space addressSpace>\nstruct cl::sycl::device_type;"
ctor: unspecified
dtor: unspecified
typedefs:
  ptr_t:
    definition: multi_ptr<cl::sycl::device_type::underlying_t, addressSpace>
    description: Pointer type used on device
  underlying_t:
    definition: volatile elemT
    description: Underlying type of the device pointer
namespace:
  - cl
  - sycl
---
