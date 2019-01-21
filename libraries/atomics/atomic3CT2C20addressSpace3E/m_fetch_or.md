---
layout: method
title: fetch_or
owner: __MISSING__
brief: Atomically bitwise-or operand with *m_data.
tags:
  - method
defined-in-file: ""
overloads:
  T fetch_or(T, cl::sycl::memory_order) volatile:
    arguments:
      - description: " the value to or with *m_data."
        name: operand
        type: T
      - description: ""
        name: unnamed-1
        type: cl::sycl::memory_order
        unnamed: true
    description: Atomically bitwise-or operand with *m_data.
    return: " the old value of *m_data."
    signature_with_names: T fetch_or(T operand, cl::sycl::memory_order) volatile
---
