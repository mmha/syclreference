---
layout: function
title: round
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t round(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Return the integral value nearest to x rounding halfway cases away from zero, regardless of the current rounding direction.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t round(F x)"
---
