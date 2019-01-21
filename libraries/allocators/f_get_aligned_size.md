---
layout: function
title: get_aligned_size
owner: __MISSING__
brief: Calculates the size that needs to be allocated for the memory to be properly aligned.
tags:
  - function
defined-in-file: ""
overloads:
  size_t get_aligned_size(const size_t, const size_t):
    arguments:
      - description: " Size in bytes the user requested. May allocate more"
        name: requestedSize
        type: const size_t
      - description: " The requirement for the allocation size to be"
        name: requiredSizeMultiplier
        type: const size_t
    description: Calculates the size that needs to be allocated for the memory to be properly aligned.
    return: " The size in bytes that needs to be allocated."
    signature_with_names: size_t get_aligned_size(const size_t requestedSize, const size_t requiredSizeMultiplier)
---
