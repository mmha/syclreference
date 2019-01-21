---
layout: function
title: sin
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF sin(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute sine.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF sin(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t sin(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute sine.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t sin(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t sin(const F)":
    arguments:
      - description: ""
        name: x
        type: const F
    description: Compute sine over an implementation-defined range.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t sin(const F x)"
---
