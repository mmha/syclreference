---
layout: method
title: get_buffer_allocator
owner: __MISSING__
brief: Creates a new base_allocator for use in a buffer object
tags:
  - method
defined-in-file: ""
overloads:
  static unique_ptr_class<cl::sycl::detail::base_allocator> get_buffer_allocator(AllocatorT):
    arguments:
      - description: " User-supplied allocator instance to be wrapped"
        name: allocator
        type: AllocatorT
    description: Creates a new base_allocator for use in a buffer object
    return: " base_allocator wrapping the user supplied allocator"
    signature_with_names: static unique_ptr_class<cl::sycl::detail::base_allocator> get_buffer_allocator(AllocatorT allocator)
---
