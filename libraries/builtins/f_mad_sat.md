---
layout: function
title: mad_sat
owner: __MISSING__
brief: Returns `a * b + c` and saturates the result.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI mad_sat(I, I, I)":
    arguments:
      - description: ""
        name: a
        type: I
      - description: ""
        name: b
        type: I
      - description: ""
        name: c
        type: I
    description: Returns `a * b + c` and saturates the result.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI mad_sat(I a, I b, I c)"
---
