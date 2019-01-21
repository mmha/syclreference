---
layout: class
title: buffer<T, dimensions, AllocatorT>
owner: __MISSING__
brief: buffer is the public interface for the buffer object implementation. The template allows the creation of specific types and number of dimensions.
tags:
  - class
defined-in-file: ""
declaration: "template <typename T, int dimensions, typename AllocatorT>\nclass cl::sycl::buffer;"
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
