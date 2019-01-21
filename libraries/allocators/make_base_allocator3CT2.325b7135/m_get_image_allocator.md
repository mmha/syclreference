---
layout: method
title: get_image_allocator
owner: __MISSING__
brief: Creates a new base_allocator for use in an image object
tags:
  - method
defined-in-file: ""
overloads:
  static unique_ptr_class<cl::sycl::detail::base_allocator> get_image_allocator(size_t, AllocatorT):
    arguments:
      - description: " When the allocation is made, the allocation size"
        name: elemSizeMultiplier
        type: size_t
      - description: " User-supplied allocator instance to be wrapped"
        name: allocator
        type: AllocatorT
    description: Creates a new base_allocator for use in an image object
    return: " base_allocator wrapping the user supplied allocator"
    signature_with_names: static unique_ptr_class<cl::sycl::detail::base_allocator> get_image_allocator(size_t elemSizeMultiplier, AllocatorT allocator)
---
