---
layout: class
title: buffer<const T, dimensions, AllocatorT>
owner: __MISSING__
brief: Specialization for const buffers, that allows the creation of buffers on the device from const data. Any allocator, but the map allocator, can be used to create host data. The allocator must remove the constness of the data in order to create temporary objects, but host accessors will only be read only always.
tags:
  - class
defined-in-file: ""
declaration: "\nclass cl::sycl::buffer;"
typedefs:
  allocator_type:
    definition: AllocatorT
    description: Helper for the user, alias for the type of the allocator
  const_reference:
    definition: const T &
    description: Helper for the user, alias for const reference to type T
  reference:
    definition: T &
    description: Helper for the user, alias for reference to type T
  value_type:
    definition: T
    description: Helper for the user, alias for type T
namespace:
  - cl
  - sycl
---
