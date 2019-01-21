---
layout: function
title: remquo
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF remquo(F, F, detail::builtin_ptr<I, AddressSpace>)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
      - description: ""
        name: quo
        type: detail::builtin_ptr<I, AddressSpace>
    description: The remquo function computes the value r such that `r = x - k * y`, where k is the integer nearest the exact value of x/y.
    return: ""
    signature_with_names: "template <typename F, typename I, access::address_space AddressSpace, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF remquo(F x, F y, detail::builtin_ptr<I, AddressSpace> quo)"
---
