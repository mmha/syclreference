---
layout: function
title: any
owner: __MISSING__
brief: Returns 1 if the most significant bit in any component of x is set; otherwise returns 0.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_igeninteger<I>::value), int> >\nint any(I)":
    arguments:
      - description: ""
        name: x
        type: I
    description: Returns 1 if the most significant bit in any component of x is set; otherwise returns 0.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_igeninteger<I>::value), int> >\nint any(I x)"
---
