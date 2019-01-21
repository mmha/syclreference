---
layout: method
title: load
owner: __MISSING__
brief: Atomically load from m_data. Calls C++11 equivalent on host, on device it either calls atomic_add with operand = 0, discarding the result.
tags:
  - method
defined-in-file: ""
overloads:
  T load(cl::sycl::memory_order) const volatile:
    arguments:
      - description: " the ordering to use. Can only be memory_order_relaxed."
        name: mem_order
        type: cl::sycl::memory_order
    description: Atomically load from m_data. Calls C++11 equivalent on host, on device it either calls atomic_add with operand = 0, discarding the result.
    return: " The value loaded from m_data."
    signature_with_names: T load(cl::sycl::memory_order mem_order) const volatile
---
