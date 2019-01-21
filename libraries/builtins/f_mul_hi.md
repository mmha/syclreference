---
layout: function
title: mul_hi
owner: __MISSING__
brief: Computes `x * y` and returns the high half of the product of `x` and `y`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI mul_hi(I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Computes `x * y` and returns the high half of the product of `x` and `y`.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI mul_hi(I x, I y)"
---
