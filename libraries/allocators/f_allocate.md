---
layout: function
title: allocate
owner: __MISSING__
brief: Allocates aligned data.
tags:
  - function
defined-in-file: ""
overloads:
  void * allocate(const size_t, const size_t, const size_t):
    arguments:
      - description: " Size in bytes the user requested. May allocate more"
        name: requestedSize
        type: const size_t
      - description: " Memory alignment boundary in bytes."
        name: alignment
        type: const size_t
      - description: " The requirement for the allocation size to be"
        name: requiredSizeMultiplier
        type: const size_t
    description: Allocates aligned data.
    return: " Pointer to allocated aligned data"
    signature_with_names: void * allocate(const size_t requestedSize, const size_t alignment, const size_t requiredSizeMultiplier)
---
