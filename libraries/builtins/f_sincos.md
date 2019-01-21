---
layout: function
title: sincos
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, access::address_space AddressSpace, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF sincos(F, detail::builtin_ptr<F, AddressSpace>)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: cosval
        type: detail::builtin_ptr<F, AddressSpace>
    description: Compute sine and cosine of x.
    return: ""
    signature_with_names: "template <typename F, access::address_space AddressSpace, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF sincos(F x, detail::builtin_ptr<F, AddressSpace> cosval)"
---
