---
layout: method
title: aligned_allocator
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  aligned_allocator(const cl::sycl::detail::aligned_mem::aligned_allocator &):
    annotation:
      - default
    arguments:
      - description: ""
        name: unnamed-0
        type: const cl::sycl::detail::aligned_mem::aligned_allocator &
        unnamed: true
    description: ""
    return: ""
    signature_with_names: aligned_allocator(const cl::sycl::detail::aligned_mem::aligned_allocator &)
  aligned_allocator(size_t, size_t):
    arguments:
      - description: " Memory alignment boundary in bytes."
        name: alignment
        type: size_t
      - description: " The requirement for the allocation size to"
        name: requiredSizeMultiplier
        type: size_t
    description: Constructs an allocator that can allocate memory aligned to a certain multiple of
    return: ""
    signature_with_names: aligned_allocator(size_t alignment, size_t requiredSizeMultiplier)
---
