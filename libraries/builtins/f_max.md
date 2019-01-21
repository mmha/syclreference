---
layout: function
title: max
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value) || (detail::builtin::is_genfloath<F1>::value && detail::builtin::is_sgenfloat<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && detail::builtin::is_sgenfloat<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && detail::builtin::is_sgenfloat<F2, double>::value)), int> >\nF max(F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F2
    description: Returns y if `x < y`, otherwise it returns x. If x or y are infinite or NaN, the return values are undefined.
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && detail::builtin::is_genfloat<F2>::value) || (detail::builtin::is_genfloath<F1>::value && detail::builtin::is_sgenfloat<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && detail::builtin::is_sgenfloat<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && detail::builtin::is_sgenfloat<F2, double>::value)), int> >\nF max(F1 x, F2 y)"
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI max(I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: I
    description: Returns y if `x < y`, otherwise it returns x.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI max(I x, I y)"
  "template <typename I, typename S, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value && detail::builtin::is_sgeninteger<S>::value)), int> >\nI max(I, S)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: y
        type: S
    description: Returns y if `x < y`, otherwise it returns x.
    return: ""
    signature_with_names: "template <typename I, typename S, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value && detail::builtin::is_sgeninteger<S>::value)), int> >\nI max(I x, S y)"
---
