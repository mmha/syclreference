---
layout: function
title: abs
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 abs(F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F2
    description: Compute absolute value of a floating-point number. Redirects to `fabs(x, y)`.
    return: ""
    signature_with_names: "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 abs(F1 x, F2 y)"
  "template <typename I, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value)), int> >\nauto abs(I) -> detail::make_genuint_t<I>":
    arguments:
      - description: " "
        name: x
        type: I
    description: Returns `|x|`
    return: " `x` if `0 "
    signature_with_names: "template <typename I, detail::enable_if_t<((detail::builtin::is_geninteger<I>::value)), int> >\nauto abs(I x) -> detail::make_genuint_t<I>"
---
