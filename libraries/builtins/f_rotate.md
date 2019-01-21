---
layout: function
title: rotate
owner: __MISSING__
brief: For each element in v, the bits are shifted left by the number of bits given by the corresponding element in i (subject to usual shift modulo rules described in section 6.3).
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI rotate(I, I)":
    arguments:
      - description: ""
        name: v
        type: I
      - description: ""
        name: i
        type: I
    description: For each element in v, the bits are shifted left by the number of bits given by the corresponding element in i (subject to usual shift modulo rules described in section 6.3).
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI rotate(I v, I i)"
---
