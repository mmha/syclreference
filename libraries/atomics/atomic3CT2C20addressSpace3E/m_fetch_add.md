---
layout: method
title: fetch_add
owner: __MISSING__
brief: Atomically add operand to *m_data. param operand the value to add to *m_data. param mem_order the ordering to use. Can only be memory_order_relaxed. return the old value of *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T fetch_add(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: ""
        name: operand
        type: T
      - description: ""
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically add operand to *m_data. param operand the value to add to *m_data. param mem_order the ordering to use. Can only be memory_order_relaxed. return the old value of *m_data.
    return: ""
    signature_with_names: T fetch_add(T operand, cl::sycl::memory_order mem_order) volatile
---
