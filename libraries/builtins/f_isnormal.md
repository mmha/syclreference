---
layout: function
title: isnormal
owner: __MISSING__
brief: Test for a normal value.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isnormal(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Test for a normal value.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isnormal(F x)"
---
