---
layout: method
title: require
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename elemT, int kDims, access::mode kMode, access::target kTarget>\nvoid require(buffer<elemT, kDims> &, const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> &)":
    arguments:
      - description: ""
        name: bufObj
        type: buffer<elemT, kDims> &
      - description: " Placeholder accessor"
        name: acc
        type: const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> &
    description: Function that registers a placeholder accessor with the handler and the associated storage. Defined in Codeplay Extension CP004. Will fail if accessor already associated with storage.
    return: ""
    signature_with_names: "template <typename elemT, int kDims, access::mode kMode, access::target kTarget>\nvoid require(buffer<elemT, kDims> & bufObj, const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> & acc)"
  "template <typename elemT, int kDims, access::mode kMode, access::target kTarget>\nvoid require(const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> &)":
    arguments:
      - description: " Placeholder accessor"
        name: acc
        type: const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> &
    description: Function that registers a placeholder accessor with the handler. Defined in Codeplay Extension CP004.
    return: ""
    signature_with_names: "template <typename elemT, int kDims, access::mode kMode, access::target kTarget>\nvoid require(const accessor<elemT, kDims, kMode, kTarget, access::placeholder::true_t> & acc)"
---
