---
layout: function
title: step
owner: __MISSING__
brief: Returns 0.0 if `x < edge`, otherwise it returns 1.0.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (std::is_same<F1, half>::value && detail::builtin::is_genfloath<F2>::value) || (std::is_same<F1, float>::value && detail::builtin::is_genfloatf<F2>::value) || (std::is_same<F1, double>::value && detail::builtin::is_genfloatd<F2>::value)), int> >\nF2 step(F1, F2)":
    arguments:
      - description: ""
        name: edge
        type: F1
      - description: ""
        name: x
        type: F2
    description: Returns 0.0 if `x < edge`, otherwise it returns 1.0.
    return: ""
    signature_with_names: "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (std::is_same<F1, half>::value && detail::builtin::is_genfloath<F2>::value) || (std::is_same<F1, float>::value && detail::builtin::is_genfloatf<F2>::value) || (std::is_same<F1, double>::value && detail::builtin::is_genfloatd<F2>::value)), int> >\nF2 step(F1 edge, F2 x)"
---
