---
layout: function
title: cast_base_allocator
owner: __MISSING__
brief: Retrieves the original user-supplied allocator from the stored detail allocator object.
tags:
  - function
defined-in-file: ""
overloads:
  "template <class AllocatorT>\nstatic AllocatorT cast_base_allocator(cl::sycl::detail::base_allocator *)":
    arguments:
      - description: " Pointer to the detail allocator object"
        name: base
        type: cl::sycl::detail::base_allocator *
    description: Retrieves the original user-supplied allocator from the stored detail allocator object.
    return: " The original allocator object"
    signature_with_names: "template <class AllocatorT>\nstatic AllocatorT cast_base_allocator(cl::sycl::detail::base_allocator * base)"
---
