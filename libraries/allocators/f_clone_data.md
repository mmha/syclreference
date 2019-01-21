---
layout: function
title: clone_data
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T, typename AllocatorT, typename Iterator>\nshared_ptr_class<void> clone_data(Iterator, Iterator, AllocatorT)":
    arguments:
      - description: ""
        name: begin
        type: Iterator
      - description: ""
        name: end
        type: Iterator
      - description: ""
        name: alloc
        type: AllocatorT
    description: ""
    return: ""
    signature_with_names: "template <typename T, typename AllocatorT, typename Iterator>\nshared_ptr_class<void> clone_data(Iterator begin, Iterator end, AllocatorT alloc)"
  "template <typename T, typename AllocatorT>\nshared_ptr_class<void> clone_data(const T *, size_t, AllocatorT)":
    arguments:
      - description: ""
        name: hostPointer
        type: const T *
      - description: ""
        name: size
        type: size_t
      - description: ""
        name: alloc
        type: AllocatorT
    description: ""
    return: ""
    signature_with_names: "template <typename T, typename AllocatorT>\nshared_ptr_class<void> clone_data(const T * hostPointer, size_t size, AllocatorT alloc)"
---
