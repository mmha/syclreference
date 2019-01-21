---
layout: class
title: get_atomic_address_space<accessTarget>
owner: __MISSING__
brief: Retrieves the address space, suitable for use in an atomic, from the access target.
tags:
  - class
defined-in-file: ""
declaration: "template <access::target accessTarget>\nstruct cl::sycl::detail::get_atomic_address_space;"
ctor: unspecified
dtor: unspecified
fields:
  value:
    description: Most targets will correspond to the global address space, even though it's only valid for access::target::global_buffer
    type: const cl::sycl::access::address_space
namespace:
  - cl
  - sycl
  - detail
---
