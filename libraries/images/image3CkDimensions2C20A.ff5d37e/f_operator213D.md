---
layout: function
title: operator!=
owner: __MISSING__
brief: Determines if lhs and rhs are not equal
tags:
  - function
defined-in-file: ""
overloads:
  bool operator!=(const image<kDimensions, AllocatorT> &, const image<kDimensions, AllocatorT> &):
    arguments:
      - description: " Left-hand-side object in comparison"
        name: lhs
        type: const image<kDimensions, AllocatorT> &
      - description: " Right-hand-side object in comparison"
        name: rhs
        type: const image<kDimensions, AllocatorT> &
    description: Determines if lhs and rhs are not equal
    return: " True if different underlying objects"
    signature_with_names: bool operator!=(const image<kDimensions, AllocatorT> & lhs, const image<kDimensions, AllocatorT> & rhs)
---
