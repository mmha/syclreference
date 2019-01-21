---
layout: function
title: mul24
owner: __MISSING__
brief: Multiply two 24-bit integer values `x` and `y`. `x` and `y` are 32-bit integers but only the low 24-bits are used to perform the multiplication.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger32bit<I>::value), int> >\nI mul24(I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Multiply two 24-bit integer values `x` and `y`. `x` and `y` are 32-bit integers but only the low 24-bits are used to perform the multiplication.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger32bit<I>::value), int> >\nI mul24(I x, I y)"
---
