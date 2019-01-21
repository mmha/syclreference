---
layout: function
title: powr
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF powr(F, F)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
    description: Compute x to the power y, where x >= 0.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF powr(F x, F y)"
  "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value)), int> >\nF powr(F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F2
    description: Compute x to the power y, where x >= 0.
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value)), int> >\nF powr(F1 x, F2 y)"
---
