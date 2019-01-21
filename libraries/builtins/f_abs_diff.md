---
layout: function
title: abs_diff
owner: __MISSING__
brief: Returns `|x - y|` without modulo overflow.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value)), int> >\nauto abs_diff(I, I) -> detail::make_genuint_t<I>":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Returns `|x - y|` without modulo overflow.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value)), int> >\nauto abs_diff(I x, I y) -> detail::make_genuint_t<I>"
---
