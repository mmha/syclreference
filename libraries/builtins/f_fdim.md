---
layout: function
title: fdim
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value)), int> >\nF fdim(F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F2
    description: "`x - y` if `x > y`, +0 if x is less than or equal to y."
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value)), int> >\nF fdim(F1 x, F2 y)"
---
