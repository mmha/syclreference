---
layout: function
title: fma
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, typename F3, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value && detail::builtin::is_genfloat<F3>::value)), int> >\nF fma(F1, F2, F3)":
    arguments:
      - description: ""
        name: a
        type: F1
      - description: ""
        name: b
        type: F2
      - description: ""
        name: c
        type: F3
    description: Returns the correctly rounded floating-point representation of the sum of c with the infinitely precise product of a and b.
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F3, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value && detail::builtin::is_genfloat<F3>::value)), int> >\nF fma(F1 a, F2 b, F3 c)"
---
