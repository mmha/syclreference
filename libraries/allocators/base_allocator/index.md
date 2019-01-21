---
layout: class
title: base_allocator
owner: __MISSING__
brief: Forward calls from the runtime-side to the user-defined allocator. This allows the internal runtime methods to call the user-defined typed allocator without passing the template tag. The isMapAllocator is used internally to determine if the allocator is a map-based one, which will enable some optimizations if possible.
tags:
  - class
defined-in-file: ""
declaration: "\nclass cl::sycl::detail::base_allocator;"
namespace:
  - cl
  - sycl
  - detail
---
