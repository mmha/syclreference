---
layout: function
title: pown
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename I, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF pown(F, I)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: I
    description: Compute x to the power y, where y is an integer.
    return: ""
    signature_with_names: "template <typename F, typename I, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF pown(F x, I y)"
---
