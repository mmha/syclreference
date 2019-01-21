---
layout: class
title: address_space_trait<dataType, cl::sycl::access::address_space::private_space>
owner: __MISSING__
brief: ""
tags:
  - class
defined-in-file: ""
declaration: "\nstruct cl::sycl::detail::address_space_trait;"
ctor: unspecified
dtor: unspecified
typedefs:
  address_space_type:
    definition: dataType
    description: ""
  original_type:
    definition: dataType
    description: ""
fields:
  hasTarget:
    description: There is no access target that would correspond to private_space, but we still need a valid target when doing SFINAE.
    type: const bool
  target:
    description: ""
    type: const cl::sycl::access::target
namespace:
  - cl
  - sycl
  - detail
---
