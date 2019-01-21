---
layout: library
title: "multi_ptr"
owner: __MISSING__
brief: __MISSING__
tags:
  - library
library-type: sourcefile
typedefs:
  constant_ptr:
    definition: multi_ptr<dataType, access::address_space::constant_space>
    description: constant_ptr, pointer class definition for data living in the OpenCL constant address space
  global_ptr:
    definition: multi_ptr<dataType, access::address_space::global_space>
    description: global_ptr pointer class definition for data pointing to the OpenCL global address space.
  local_ptr:
    definition: multi_ptr<dataType, access::address_space::local_space>
    description: local_ptr pointer class definition for data pointing to the OpenCL local address space
  private_ptr:
    definition: multi_ptr<dataType, access::address_space::private_space>
    description: private_ptr, pointer class definition for data pointing to the OpenCL private address space
---
