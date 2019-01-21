---
layout: function
title: log10
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t log10(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute a base 10 logarithm.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t log10(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t log10(const F)":
    arguments:
      - description: ""
        name: x
        type: const F
    description: Compute a base 10 logarithm.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t log10(const F x)"
---
