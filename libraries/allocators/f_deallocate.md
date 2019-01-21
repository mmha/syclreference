---
layout: function
title: deallocate
owner: __MISSING__
brief: Deallocates aligned data.
tags:
  - function
defined-in-file: ""
overloads:
  void deallocate(void *, const size_t, const size_t):
    arguments:
      - description: " Pointer to allocated aligned data"
        name: memptr
        type: void *
      - description: " Size in bytes the user requested. May deallocate more"
        name: requestedSize
        type: const size_t
      - description: " The requirement for the allocation size to be"
        name: requiredSizeMultiplier
        type: const size_t
    description: Deallocates aligned data.
    return: ""
    signature_with_names: void deallocate(void * memptr, const size_t requestedSize, const size_t requiredSizeMultiplier)
---
