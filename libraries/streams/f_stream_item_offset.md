---
layout: function
title: stream_item_offset
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <int dimensions>\nvoid stream_item_offset(const cl::sycl::stream &, const item<dimensions, false> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " item object"
        name: rhs
        type: const item<dimensions, false> &
    description: Streams an item offset.
    return: ""
    signature_with_names: "template <int dimensions>\nvoid stream_item_offset(const cl::sycl::stream & os, const item<dimensions, false> & rhs)"
  "template <int dimensions>\nvoid stream_item_offset(const cl::sycl::stream &, const item<dimensions, true> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " item object"
        name: rhs
        type: const item<dimensions, true> &
    description: Streams an item offset.
    return: ""
    signature_with_names: "template <int dimensions>\nvoid stream_item_offset(const cl::sycl::stream & os, const item<dimensions, true> & rhs)"
---
