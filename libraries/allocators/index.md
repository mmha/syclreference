---
layout: library
title: "Allocators"
owner: __MISSING__
brief: __MISSING__
tags:
  - library
library-type: sourcefile
typedefs:
  buffer_allocator:
    definition: cl::sycl::default_allocator
    description: ""
  default_allocator:
    definition: detail::aligned_mem::aligned_allocator
    description: Default SYCL allocator uses the aligned allocated, but also removes the constness of the type.
  image_allocator:
    definition: cl::sycl::default_allocator
    description: ""
---
