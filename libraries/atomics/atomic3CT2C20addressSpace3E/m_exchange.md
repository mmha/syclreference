---
layout: method
title: exchange
owner: __MISSING__
brief: Atomically exchange operand with *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T exchange(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to store in *m_data."
        name: operand
        type: T
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically exchange operand with *m_data.
    return: " The old value of *m_data."
    signature_with_names: T exchange(T operand, cl::sycl::memory_order mem_order) volatile
---
