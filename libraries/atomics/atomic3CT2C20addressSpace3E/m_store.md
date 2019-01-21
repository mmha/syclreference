---
layout: method
title: store
owner: __MISSING__
brief: Atomically store operand in m_data. Calls C++11 equivalent on host, on device it calls exchange, discarding the result.
tags:
  - method
defined-in-file: ""
overloads:
  void store(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to store in m_data."
        name: operand
        type: T
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically store operand in m_data. Calls C++11 equivalent on host, on device it calls exchange, discarding the result.
    return: ""
    signature_with_names: void store(T operand, cl::sycl::memory_order mem_order) volatile
---
