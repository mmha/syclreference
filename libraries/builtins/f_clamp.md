---
layout: function
title: clamp
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 clamp(F1, F2, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: minval
        type: F2
      - description: ""
        name: maxval
        type: F2
    description: Returns `fmin(fmax(x, minval), maxval)`.
    return: ""
    signature_with_names: "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 clamp(F1 x, F2 minval, F2 maxval)"
  "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI clamp(I, I, I)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: minval
        type: I
      - description: ""
        name: maxval
        type: I
    description: Returns `min(max(x, minval), maxval)`. Results are undefined if `minval > maxval`.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_geninteger<I>::value), int> >\nI clamp(I x, I minval, I maxval)"
  "template <typename I, typename S, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value && detail::builtin::is_sgeninteger<S>::value)), int> >\nI clamp(I, S, S)":
    arguments:
      - description: ""
        name: x
        type: I
      - description: ""
        name: minval
        type: S
      - description: ""
        name: maxval
        type: S
    description: Returns `min(max(x, minval), maxval)`. Results are undefined if `minval > maxval`.
    return: ""
    signature_with_names: "template <typename I, typename S, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value && detail::builtin::is_sgeninteger<S>::value)), int> >\nI clamp(I x, S minval, S maxval)"
---
