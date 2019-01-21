---
layout: function
title: signbit
owner: __MISSING__
brief: Test for sign bit. The scalar version of the function returns a 1 if the sign bit in the float is set else returns 0.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t signbit(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Test for sign bit. The scalar version of the function returns a 1 if the sign bit in the float is set else returns 0.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t signbit(F x)"
---
