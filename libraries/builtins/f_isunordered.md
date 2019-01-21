---
layout: function
title: isunordered
owner: __MISSING__
brief: Test if arguments are unordered.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isunordered(F, F)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
    description: Test if arguments are unordered.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isunordered(F x, F y)"
---
