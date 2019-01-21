---
layout: function
title: is_aligned
owner: __MISSING__
brief: Checks whether the pointer points to aligned data
tags:
  - function
defined-in-file: ""
overloads:
  bool is_aligned(void *, const size_t, const size_t, const size_t):
    arguments:
      - description: " Pointer to allocated data"
        name: p
        type: void *
      - description: " Total allocated size of the buffer in bytes"
        name: totalSizeInBytes
        type: const size_t
      - description: " Memory alignment boundary in bytes."
        name: alignment
        type: const size_t
      - description: " The requirement for the allocation size to be"
        name: requiredSizeMultiplier
        type: const size_t
    description: Checks whether the pointer points to aligned data
    return: ""
    signature_with_names: bool is_aligned(void * p, const size_t totalSizeInBytes, const size_t alignment, const size_t requiredSizeMultiplier)
---
