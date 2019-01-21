---
layout: function
title: add_sat
owner: __MISSING__
brief: Returns `x + y` and saturates the result.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI add_sat(I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Returns `x + y` and saturates the result.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI add_sat(I x, I y)"
---
