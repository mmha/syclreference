---
layout: function
title: frexp
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF frexp(F, detail::builtin_ptr<I, AddressSpace>)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: exp
        type: detail::builtin_ptr<I, AddressSpace>
    description: Extract mantissa and exponent from x.
    return: ""
    signature_with_names: "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF frexp(F x, detail::builtin_ptr<I, AddressSpace> exp)"
---
