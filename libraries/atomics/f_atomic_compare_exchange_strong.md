---
layout: function
title: atomic_compare_exchange_strong
owner: __MISSING__
brief: Global function atomic_compare_exchange. Calls compare_exchange on SYCL atomic object.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T, access::address_space addressSpace>\ncl::sycl::cl_bool atomic_compare_exchange_strong(atomic<T, addressSpace>, T *, T, cl::sycl::memory_order, cl::sycl::memory_order)":
    arguments:
      - description: " The atomic object to compare_exchange with"
        name: object
        type: atomic<T, addressSpace>
      - description: ""
        name: expected
        type: T *
      - description: ""
        name: desired
        type: T
      - description: ""
        name: success
        type: cl::sycl::memory_order
      - description: ""
        name: fail
        type: cl::sycl::memory_order
    description: Global function atomic_compare_exchange. Calls compare_exchange on SYCL atomic object.
    return: " Whether comparison succeeds or fails"
    signature_with_names: "template <typename T, access::address_space addressSpace>\ncl::sycl::cl_bool atomic_compare_exchange_strong(atomic<T, addressSpace> object, T * expected, T desired, cl::sycl::memory_order success, cl::sycl::memory_order fail)"
---
