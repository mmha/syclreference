---
layout: method
title: atomic<T, addressSpace>
owner: __MISSING__
brief: Constructs an instance of SYCL atomic which is associated with the pointer ptr, converted to a pointer of data type T.
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  "template <typename pointerT>\natomic<T, addressSpace>(multi_ptr<pointerT, addressSpace>)":
    arguments:
      - description: " Pointer to be used in an atomic manner"
        name: ptr
        type: multi_ptr<pointerT, addressSpace>
    description: Constructs an instance of SYCL atomic which is associated with the pointer ptr, converted to a pointer of data type T.
    return: ""
    signature_with_names: "template <typename pointerT>\natomic<T, addressSpace>(multi_ptr<pointerT, addressSpace> ptr)"
---
