---
layout: function
title: islessgreater
owner: __MISSING__
brief: Returns the component-wise compare of `(x < y) || (x > y)`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> islessgreater(F, F)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
    description: Returns the component-wise compare of `(x < y) || (x > y)`.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> islessgreater(F x, F y)"
---
