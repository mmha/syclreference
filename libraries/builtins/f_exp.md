---
layout: function
title: exp
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t exp(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute the base-e exponential of x.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t exp(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t exp(const F)":
    arguments:
      - description: ""
        name: x
        type: const F
    description: Compute the base-e exponential of x.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t exp(const F x)"
---
