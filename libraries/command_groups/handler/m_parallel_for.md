---
layout: method
title: parallel_for
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <int dimensions>\nvoid parallel_for(const nd_range<dimensions> &, cl::sycl::kernel *)":
    arguments:
      - description: ""
        name: ndRange
        type: const nd_range<dimensions> &
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: ""
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const nd_range<dimensions> & ndRange, cl::sycl::kernel * syclKernel)"
  "template <int dimensions>\nvoid parallel_for(const nd_range<dimensions> &, cl::sycl::kernel)":
    arguments:
      - description: " Dimensions of the global and local work groups"
        name: ndRange
        type: const nd_range<dimensions> &
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
    description: Parallel_for will enqueue the precompiled kernel executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const nd_range<dimensions> & ndRange, cl::sycl::kernel syclKernel)"
  "template <int dimensions>\nvoid parallel_for(const range<dimensions> &, cl::sycl::kernel *)":
    arguments:
      - description: ""
        name: range
        type: const range<dimensions> &
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: COMPUTECPP_DEV
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const range<dimensions> & range, cl::sycl::kernel * syclKernel)"
  "template <int dimensions>\nvoid parallel_for(const range<dimensions> &, cl::sycl::kernel)":
    arguments:
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
    description: Parallel_for will enqueue the precompiled kernel executed a number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const range<dimensions> & range, cl::sycl::kernel syclKernel)"
  "template <int dimensions>\nvoid parallel_for(const range<dimensions> &, id<dimensions>, cl::sycl::kernel *)":
    arguments:
      - description: ""
        name: range
        type: const range<dimensions> &
      - description: ""
        name: offset
        type: id<dimensions>
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: ""
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const range<dimensions> & range, id<dimensions> offset, cl::sycl::kernel * syclKernel)"
  "template <int dimensions>\nvoid parallel_for(const range<dimensions> &, id<dimensions>, cl::sycl::kernel)":
    arguments:
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The offset into the data being executed"
        name: offset
        type: id<dimensions>
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
    description: Parallel_for will enqueue the precompiled kernel executed a number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for(const range<dimensions> & range, id<dimensions> offset, cl::sycl::kernel syclKernel)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel, const nd_range<dimensions> &, const functorT &)":
    arguments:
      - description: " The precompiled kernel to be enqueued"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " Dimensions of the global and local work groups"
        name: ndRange
        type: const nd_range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the kernel number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel syclKernel, const nd_range<dimensions> & ndRange, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel, const range<dimensions> &, const functorT &)":
    arguments:
      - description: " The precompiled kernel which is being run"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the precompiled kernel executed a number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel syclKernel, const range<dimensions> & range, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel, const range<dimensions> &, const id<dimensions> &, const functorT &)":
    arguments:
      - description: " The precompiled kernel which is being run"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The offset into the data being executed"
        name: offset
        type: const id<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the precompiled kernel executed a number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(cl::sycl::kernel syclKernel, const range<dimensions> & range, const id<dimensions> & offset, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const nd_range<dimensions> &, const functorT &)":
    arguments:
      - description: " Dimensions of the global and local work groups"
        name: ndRange
        type: const nd_range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the kernel number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const nd_range<dimensions> & ndRange, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const range<dimensions> &, const functorT &)":
    arguments:
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the kernel number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const range<dimensions> & range, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const range<dimensions> &, const id<dimensions> &, const functorT &)":
    arguments:
      - description: " Dimensions of the global work group"
        name: range
        type: const range<dimensions> &
      - description: " The offset into the data being executed"
        name: offset
        type: const id<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: Parallel_for will enqueue the kernel number of instances working in parallel over the number of global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for(const range<dimensions> & range, const id<dimensions> & offset, const functorT & functor)"
---
