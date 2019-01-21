---
layout: method
title: nd_range<dimensions>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  nd_range<dimensions>(const detail::nd_range_base &):
    arguments:
      - description: " The nd_range to copy"
        name: ndRangeBase
        type: const detail::nd_range_base &
    description: Copy constructor. Create a copy of another nd_range.
    return: ""
    signature_with_names: nd_range<dimensions>(const detail::nd_range_base & ndRangeBase)
  nd_range<dimensions>(const range<dimensions>, const range<dimensions>, const id<dimensions>):
    arguments:
      - description: " The global "
        name: globalRange
        type: const range<dimensions>
      - description: " The local "
        name: localRange
        type: const range<dimensions>
      - description: " The global offset (optional, default to 0)"
        name: globalOffset
        type: const id<dimensions>
    description: Construct a nd_range object specifying the global and local range and an optional offset. Note that the global range must divisible by the local range in order to be usable by a
    return: ""
    signature_with_names: nd_range<dimensions>(const range<dimensions> globalRange, const range<dimensions> localRange, const id<dimensions> globalOffset)
---
