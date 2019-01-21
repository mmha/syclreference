---
layout: function
title: isordered
owner: __MISSING__
brief: Test if arguments are ordered.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isordered(F, F)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: y
        type: F
    description: Test if arguments are ordered.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\ndetail::matching_integral_t<F> isordered(F x, F y)"
---
