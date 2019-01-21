---
layout: method
title: single_task
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename nameT, typename functorT>\nvoid single_task(cl::sycl::kernel, const functorT &)":
    arguments:
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: This function effectively just launches a single thread to execute the kernel in serial asynchronously to the host execution. This function takes in a precompiled kernel created using
    return: ""
    signature_with_names: "template <typename nameT, typename functorT>\nvoid single_task(cl::sycl::kernel syclKernel, const functorT & functor)"
  "template <typename nameT, typename functorT>\nvoid single_task(const functorT &)":
    arguments:
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: This function effectively just launches a single thread to execute the kernel in serial asynchronously to the host execution.
    return: ""
    signature_with_names: "template <typename nameT, typename functorT>\nvoid single_task(const functorT & functor)"
  void single_task(cl::sycl::kernel *):
    arguments:
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: COMPUTECPP_DEV
    return: ""
    signature_with_names: void single_task(cl::sycl::kernel * syclKernel)
  void single_task(cl::sycl::kernel):
    arguments:
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
    description: This function effectively just launches a single thread to execute the kernel in serial asynchronously to the host execution. This function takes in a precompiled kernel created using
    return: ""
    signature_with_names: void single_task(cl::sycl::kernel syclKernel)
---
