---
layout: function
title: lgamma_r
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF lgamma_r(F, detail::builtin_ptr<I, AddressSpace>)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: signp
        type: detail::builtin_ptr<I, AddressSpace>
    description: Log gamma function.
    return: ""
    signature_with_names: "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF lgamma_r(F x, detail::builtin_ptr<I, AddressSpace> signp)"
---
