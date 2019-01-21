---
layout: method
title: fetch_sub
owner: __MISSING__
brief: Atomically subtract operand from *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T fetch_sub(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to subtract from *m_data."
        name: operand
        type: T
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically subtract operand from *m_data.
    return: " the old value of m_data."
    signature_with_names: T fetch_sub(T operand, cl::sycl::memory_order mem_order) volatile
---
