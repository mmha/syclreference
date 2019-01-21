---
layout: function
title: rootn
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename I, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value , detail::builtin::is_genint<I>::value), int> >\nF rootn(F, I)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: I
    description: Compute x to the power 1/y.
    return: ""
    signature_with_names: "template <typename F, typename I, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value , detail::builtin::is_genint<I>::value), int> >\nF rootn(F x, I y)"
---
