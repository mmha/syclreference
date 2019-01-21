---
layout: function
title: tan
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF tan(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute tangent.
    return: ""
    signature_with_names: "template <typename F, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nF tan(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t tan(F)":
    arguments:
      - description: ""
        name: x
        type: F
    description: Compute tangent.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nreturn_t tan(F x)"
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t tan(const F)":
    arguments:
      - description: ""
        name: x
        type: const F
    description: Compute tangent over an implementation-defined range.
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_genfloatf<F>::value), int> >\nreturn_t tan(const F x)"
---
