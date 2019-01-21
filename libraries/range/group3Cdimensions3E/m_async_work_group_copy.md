---
layout: method
title: async_work_group_copy
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(global_ptr<dataT>, local_ptr<dataT>, size_t) const":
    arguments:
      - description: " Pointer to the destination in global memory"
        name: dest
        type: global_ptr<dataT>
      - description: " Pointer to the source in local memory"
        name: src
        type: local_ptr<dataT>
      - description: " Number of elements to copy"
        name: numElements
        type: size_t
    description: Asynchronous work group copy from a local pointer to global.
    return: ""
    signature_with_names: "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(global_ptr<dataT> dest, local_ptr<dataT> src, size_t numElements) const"
  "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(global_ptr<dataT>, local_ptr<dataT>, size_t, size_t) const":
    arguments:
      - description: " Pointer to the destination in global memory"
        name: dest
        type: global_ptr<dataT>
      - description: " Pointer to the source in local memory"
        name: src
        type: local_ptr<dataT>
      - description: " Number of elements to copy"
        name: numElements
        type: size_t
      - description: " Stride in the destination"
        name: destStride
        type: size_t
    description: Asynchronous work group copy from a local pointer to global.
    return: ""
    signature_with_names: "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(global_ptr<dataT> dest, local_ptr<dataT> src, size_t numElements, size_t destStride) const"
  "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(local_ptr<dataT>, global_ptr<dataT>, size_t) const":
    arguments:
      - description: " Pointer to the destination in local memory"
        name: dest
        type: local_ptr<dataT>
      - description: " Pointer to the source in global memory"
        name: src
        type: global_ptr<dataT>
      - description: " Number of elements to copy"
        name: numElements
        type: size_t
    description: Asynchronous work group copy from a global pointer to local.
    return: ""
    signature_with_names: "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(local_ptr<dataT> dest, global_ptr<dataT> src, size_t numElements) const"
  "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(local_ptr<dataT>, global_ptr<dataT>, size_t, size_t) const":
    arguments:
      - description: " Pointer to the destination in local memory"
        name: dest
        type: local_ptr<dataT>
      - description: " Pointer to the source in global memory"
        name: src
        type: global_ptr<dataT>
      - description: " Number of elements to copy"
        name: numElements
        type: size_t
      - description: ""
        name: srcStride
        type: size_t
    description: Asynchronous work group copy from a global pointer to local.
    return: ""
    signature_with_names: "template <typename dataT>\ncl::sycl::device_event async_work_group_copy(local_ptr<dataT> dest, global_ptr<dataT> src, size_t numElements, size_t srcStride) const"
---
