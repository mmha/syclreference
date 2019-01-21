---
layout: method
title: fetch_xor
owner: __MISSING__
brief: Atomically bitwise-xor operand with *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T fetch_xor(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to xor with *m_data."
        name: operand
        type: T
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically bitwise-xor operand with *m_data.
    return: " the old value of *m_data."
    signature_with_names: T fetch_xor(T operand, cl::sycl::memory_order mem_order) volatile
---
