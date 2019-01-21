---
layout: class
title: atomic<T, addressSpace>
owner: __MISSING__
brief: Implementation of the SYCL atomic class according to 1.2 spec. (section 3.8). On host, calls C++ atomic functions on an std::atomic; on device uses SPIR-mangled OpenCL 1.2 functions to achieve same result.
tags:
  - class
defined-in-file: ""
declaration: "template <typename T, access::address_space addressSpace>\nstruct cl::sycl::atomic;"
dtor: unspecified
namespace:
  - cl
  - sycl
---
