---
layout: method
title: parallel_for_work_group
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> &, cl::sycl::kernel *)":
    arguments:
      - description: ""
        name: numGroups
        type: const range<dimensions> &
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: ""
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> & numGroups, cl::sycl::kernel * syclKernel)"
  "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> &, cl::sycl::kernel)":
    arguments:
      - description: " Dimensions of the global and local work groups"
        name: numGroups
        type: const range<dimensions> &
      - description: " The precompiled kernel which is being run"
        name: syclKernel
        type: cl::sycl::kernel
    description: parallel_for_work_group will enqueue the precompiled kernel syclKernel to be executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> & numGroups, cl::sycl::kernel syclKernel)"
  "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> &, const range<dimensions> &, cl::sycl::kernel *)":
    arguments:
      - description: ""
        name: numGroups
        type: const range<dimensions> &
      - description: ""
        name: groupSize
        type: const range<dimensions> &
      - description: ""
        name: syclKernel
        type: cl::sycl::kernel *
    description: ""
    return: ""
    signature_with_names: "template <int dimensions>\nvoid parallel_for_work_group(const range<dimensions> & numGroups, const range<dimensions> & groupSize, cl::sycl::kernel * syclKernel)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(cl::sycl::kernel, const range<dimensions> &, const functorT &)":
    arguments:
      - description: " The precompiled kernel which is being run"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " Dimensions of the global work groups"
        name: range
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: parallel_for_work_group will enqueue the precompiled kernel syclKernel to be executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(cl::sycl::kernel syclKernel, const range<dimensions> & range, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(cl::sycl::kernel, const range<dimensions> &, const range<dimensions> &, const functorT &)":
    arguments:
      - description: " The precompiled kernel which is being run"
        name: syclKernel
        type: cl::sycl::kernel
      - description: " dimensions of the work groups being launched"
        name: numGroups
        type: const range<dimensions> &
      - description: " each work group will launch work-items of dimension of"
        name: groupSize
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: parallel_for_work_group will enqueue the precompiled kernel syclKernel to be executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(cl::sycl::kernel syclKernel, const range<dimensions> & numGroups, const range<dimensions> & groupSize, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(const range<dimensions> &, const functorT &)":
    arguments:
      - description: " Dimensions of the global and local work groups"
        name: range
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: parallel_for_work_group will enqueue the kernel be executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(const range<dimensions> & range, const functorT & functor)"
  "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(const range<dimensions> &, const range<dimensions> &, const functorT &)":
    arguments:
      - description: " dimensions of the work groups being launched"
        name: numGroups
        type: const range<dimensions> &
      - description: " each work group will launch work-items of dimension of"
        name: groupSize
        type: const range<dimensions> &
      - description: " The kernel being enqueued"
        name: functor
        type: const functorT &
    description: parallel_for_work_group will enqueue the precompiled kernel syclKernel to be executed a number of instances working in parallel over the number of local and global work items specified by
    return: ""
    signature_with_names: "template <typename nameT, typename functorT, int dimensions>\nvoid parallel_for_work_group(const range<dimensions> & numGroups, const range<dimensions> & groupSize, const functorT & functor)"
---
