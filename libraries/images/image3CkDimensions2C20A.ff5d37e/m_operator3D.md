---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  image<kDimensions, AllocatorT> & operator=(const image<kDimensions, AllocatorT> &):
    arguments:
      - description: ""
        name: rhs
        type: const image<kDimensions, AllocatorT> &
    description: Copy assignment.Copies the image descriptor of the original image. After the copy, both image object will point to the same underlying memory.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT> & operator=(const image<kDimensions, AllocatorT> & rhs)
  image<kDimensions, AllocatorT> & operator=(image<kDimensions, AllocatorT> &&):
    arguments:
      - description: ""
        name: rhs
        type: image<kDimensions, AllocatorT> &&
    description: Move Assignment. Moves the image descriptor of the original image. After the move, rhs will be invalid.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT> & operator=(image<kDimensions, AllocatorT> && rhs)
---
