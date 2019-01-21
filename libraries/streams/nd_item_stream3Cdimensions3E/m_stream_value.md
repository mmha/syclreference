---
layout: method
title: stream_value
owner: __MISSING__
brief: Streams an nd_item object into a stream object
tags:
  - method
defined-in-file: ""
overloads:
  static const cl::sycl::stream & stream_value(const cl::sycl::stream &, const nd_item_stream<dimensions> &):
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " nd_item object"
        name: rhs
        type: const nd_item_stream<dimensions> &
    description: Streams an nd_item object into a stream object
    return: " Original stream object"
    signature_with_names: static const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const nd_item_stream<dimensions> & rhs)
---
