---
layout: function
title: ldexp
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF ldexp(F, const int)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: k
        type: const int
    description: Multiply x by 2 to the power k.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF ldexp(F x, const int k)"
  "template <typename F, typename I, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF ldexp(F, I)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: k
        type: I
    description: Multiply x by 2 to the power k.
    return: ""
    signature_with_names: "template <typename F, typename I, detail::enable_if_t<((detail::builtin::is_genfloat<F>::value && detail::builtin::is_genint<I>::value)), int> >\nF ldexp(F x, I k)"
---
