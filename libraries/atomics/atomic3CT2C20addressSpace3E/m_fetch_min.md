---
layout: method
title: fetch_min
owner: __MISSING__
brief: Atomically compare operand to *m_data, storing the smaller of the two in *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T fetch_min(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to compare to *m_data."
        name: operand
        type: T
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically compare operand to *m_data, storing the smaller of the two in *m_data.
    return: " the old value of *m_data."
    signature_with_names: T fetch_min(T operand, cl::sycl::memory_order mem_order) volatile
---
