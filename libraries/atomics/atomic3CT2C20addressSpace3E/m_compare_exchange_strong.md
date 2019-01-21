---
layout: method
title: compare_exchange_strong
owner: __MISSING__
brief: Atomically compare and optionally exchange expected with *m_data. Calls C++11 equivalent on host, has to be implemented "by hand" on device because OpenCL 1.2 and C++ 11 have different semantics for compare and exchange. If *m_data == expected, performs *m_data = desired and returns true. Otherwise, performs expected = *m_data and returns false.
tags:
  - method
defined-in-file: ""
overloads:
  cl::sycl::cl_bool compare_exchange_strong(T &, T, cl::sycl::memory_order, cl::sycl::memory_order) volatile:
    arguments:
      - description: " The value to compare against *m_data."
        name: expected
        type: T &
      - description: " The value to store in *m_data on success."
        name: desired
        type: T
      - description: " the ordering to use when comparison succeeds. Can only"
        name: success
        type: cl::sycl::memory_order
      - description: " the ordering to use when comparison fails. Can only"
        name: fail
        type: cl::sycl::memory_order
    description: Atomically compare and optionally exchange expected with *m_data. Calls C++11 equivalent on host, has to be implemented "by hand" on device because OpenCL 1.2 and C++ 11 have different semantics for compare and exchange. If *m_data == expected, performs *m_data = desired and returns true. Otherwise, performs expected = *m_data and returns false.
    return: " True if comparison succeeds, false if it fails."
    signature_with_names: cl::sycl::cl_bool compare_exchange_strong(T & expected, T desired, cl::sycl::memory_order success, cl::sycl::memory_order fail) volatile
---
