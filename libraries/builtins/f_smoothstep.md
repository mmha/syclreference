---
layout: function
title: smoothstep
owner: __MISSING__
brief: Returns 0.0 if `x <= edge0` and 1.0 if `x >= edge1` and performs smooth Hermite interpolation between 0 and 1 when `edge0 < x < edge1`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (std::is_same<F1, half>::value && detail::builtin::is_genfloath<F2>::value) || (std::is_same<F1, float>::value && detail::builtin::is_genfloatf<F2>::value) || (std::is_same<F1, double>::value && detail::builtin::is_genfloatd<F2>::value)), int> >\nF2 smoothstep(F1, F1, F2)":
    arguments:
      - description: ""
        name: edge0
        type: F1
      - description: ""
        name: edge1
        type: F1
      - description: ""
        name: x
        type: F2
    description: Returns 0.0 if `x <= edge0` and 1.0 if `x >= edge1` and performs smooth Hermite interpolation between 0 and 1 when `edge0 < x < edge1`.
    return: ""
    signature_with_names: "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (std::is_same<F1, half>::value && detail::builtin::is_genfloath<F2>::value) || (std::is_same<F1, float>::value && detail::builtin::is_genfloatf<F2>::value) || (std::is_same<F1, double>::value && detail::builtin::is_genfloatd<F2>::value)), int> >\nF2 smoothstep(F1 edge0, F1 edge1, F2 x)"
---
