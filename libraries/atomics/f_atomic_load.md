---
layout: function
title: atomic_load
owner: __MISSING__
brief: Returns *object
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T, access::address_space addressSpace>\nT atomic_load(atomic<T, addressSpace>, cl::sycl::memory_order)":
    arguments:
      - description: " The atomic object to load from"
        name: object
        type: atomic<T, addressSpace>
      - description: " The memory ordering to use. Only memory_order_relaxed"
        name: mem_order
        type: cl::sycl::memory_order
    description: Returns *object
    return: " *object"
    signature_with_names: "template <typename T, access::address_space addressSpace>\nT atomic_load(atomic<T, addressSpace> object, cl::sycl::memory_order mem_order)"
---
