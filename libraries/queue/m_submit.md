---
layout: method
title: submit
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename T>\ncl::sycl::event submit(T)":
    arguments:
      - description: " The command group functor"
        name: cgf
        type: T
    description: Submits a command group functor to execution.
    return: ""
    signature_with_names: "template <typename T>\ncl::sycl::event submit(T cgf)"
  "template <typename T>\ncl::sycl::event submit(T, const cl::sycl::queue &)":
    arguments:
      - description: " The command group functor"
        name: cgf
        type: T
      - description: " The fallback queue to use in case of error."
        name: queue
        type: const cl::sycl::queue &
    description: Submits a command group functor to execution with a fallback queue. If an error occur during the execution of the kernel on the current queue, the runtime will try to run the kernel on the fallback queue.
    return: ""
    signature_with_names: "template <typename T>\ncl::sycl::event submit(T cgf, const cl::sycl::queue & queue)"
---
