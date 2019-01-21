---
layout: function
title: ilogb
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::correct_int_t<F> ilogb(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Return the exponent as an integer value.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::correct_int_t<F> ilogb(F x)"
---
