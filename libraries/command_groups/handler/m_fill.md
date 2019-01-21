---
layout: method
title: fill
owner: __MISSING__
brief: Fills the data associated with the accessor using the scalar value.
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename TAcc, typename T, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid fill(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>, T)":
    arguments:
      - description: " Accessor with the data that will be filled"
        name: acc
        type: accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>
      - description: " Scalar used to fill the device data with"
        name: val
        type: T
    description: Fills the data associated with the accessor using the scalar value.
    return: ""
    signature_with_names: "template <typename TAcc, typename T, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid fill(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder> acc, T val)"
---
