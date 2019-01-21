---
layout: function
title: atomic_fetch_add
owner: __MISSING__
brief: Global function atomic_add. Calls add on SYCL atomic object.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T, access::address_space addressSpace>\nT atomic_fetch_add(atomic<T, addressSpace>, T, cl::sycl::memory_order)":
    arguments:
      - description: " The atomic object to add to"
        name: object
        type: atomic<T, addressSpace>
      - description: ""
        name: operand
        type: T
      - description: " The memory ordering to use. Only memory_order_relaxed"
        name: mem_order
        type: cl::sycl::memory_order
    description: Global function atomic_add. Calls add on SYCL atomic object.
    return: " The old value of *object"
    signature_with_names: "template <typename T, access::address_space addressSpace>\nT atomic_fetch_add(atomic<T, addressSpace> object, T operand, cl::sycl::memory_order mem_order)"
---
