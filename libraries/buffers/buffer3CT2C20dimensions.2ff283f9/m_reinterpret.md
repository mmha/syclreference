---
layout: method
title: reinterpret
owner: __MISSING__
brief: Creates and returns a reinterpreted SYCL buffer with the type specified by ReinterpretT, dimensions specified by ReinterpretDim and range specified by reinterpretRange
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename ReinterpretT, int ReinterpretDim>\nbuffer<ReinterpretT, ReinterpretDim, AllocatorT> reinterpret(range<ReinterpretDim>) const":
    arguments:
      - description: " the range that the new buffer will use."
        name: reinterpretRange
        type: range<ReinterpretDim>
    description: Creates and returns a reinterpreted SYCL buffer with the type specified by ReinterpretT, dimensions specified by ReinterpretDim and range specified by reinterpretRange
    return: " the reinterpreted buffer with the requested parameters"
    signature_with_names: "template <typename ReinterpretT, int ReinterpretDim>\nbuffer<ReinterpretT, ReinterpretDim, AllocatorT> reinterpret(range<ReinterpretDim> reinterpretRange) const"
---
