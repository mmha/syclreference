---
layout: function
title: islessequal
owner: __MISSING__
brief: Returns the component-wise compare of `x <= y`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> islessequal(F, F)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
    description: Returns the component-wise compare of `x <= y`.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> islessequal(F x, F y)"
---
