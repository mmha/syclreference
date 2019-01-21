---
layout: method
title: update_host
owner: __MISSING__
brief: Updates the device data with the current host accessor
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename T, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder>\nvoid update_host(accessor<T, dims, accessMode, accessTarget, isPlaceholder>)":
    arguments:
      - description: ""
        name: acc
        type: accessor<T, dims, accessMode, accessTarget, isPlaceholder>
    description: Updates the device data with the current host accessor
    return: ""
    signature_with_names: "template <typename T, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder>\nvoid update_host(accessor<T, dims, accessMode, accessTarget, isPlaceholder> acc)"
---
