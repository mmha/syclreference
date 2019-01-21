---
layout: function
title: isfinite
owner: __MISSING__
brief: Test for finite value.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isfinite(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Test for finite value.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isfinite(F x)"
---
