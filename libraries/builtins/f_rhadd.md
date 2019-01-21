---
layout: function
title: rhadd
owner: __MISSING__
brief: Returns `(x + y + 1) >> 1`. The intermediate sum does not modulo overflow.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI rhadd(I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Returns `(x + y + 1) >> 1`. The intermediate sum does not modulo overflow.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI rhadd(I x, I y)"
---
