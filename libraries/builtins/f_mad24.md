---
layout: function
title: mad24
owner: __MISSING__
brief: Multipy two 24-bit integer values `x` and `y` and add the 32-bit integer result to the 32-bit integer `z`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger32bit<I>::value), int> >\nI mad24(I, I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
      - description: ""
        name: z
        type: I
    description: Multipy two 24-bit integer values `x` and `y` and add the 32-bit integer result to the 32-bit integer `z`.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger32bit<I>::value), int> >\nI mad24(I x, I y, I z)"
---
