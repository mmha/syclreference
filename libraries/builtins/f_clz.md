---
layout: function
title: clz
owner: __MISSING__
brief: Returns the number of leading 0-bits in `x`, starting at the most significant bit position.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, typename return_t, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nreturn_t clz(I)":
    arguments:
      - description: ""
        name: x
        type: I
    description: Returns the number of leading 0-bits in `x`, starting at the most significant bit position.
    return: ""
    signature_with_names: "template <typename I, typename return_t, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nreturn_t clz(I x)"
---
