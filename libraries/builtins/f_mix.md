---
layout: function
title: mix
owner: __MISSING__
brief: "Returns the linear blend of x&y implemented as: x + (y - x) * a. a must be a value in the range `0.0 ... 1.0`. If a is not in the range 0.0 ... 1.0, the return values are undefined."
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 mix(F1, F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F1
      - description: ""
        name: a
        type: F2
    description: "Returns the linear blend of x&y implemented as: x + (y - x) * a. a must be a value in the range `0.0 ... 1.0`. If a is not in the range 0.0 ... 1.0, the return values are undefined."
    return: ""
    signature_with_names: "template <typename F1, typename F2, detail::enable_if_t<((detail::builtin::is_genfloat<F1>::value && std::is_same<F1, F2>::value) || (detail::builtin::is_genfloath<F1>::value && std::is_same<F2, half>::value) || (detail::builtin::is_genfloatf<F1>::value && std::is_same<F2, float>::value) || (detail::builtin::is_genfloatd<F1>::value && std::is_same<F2, double>::value)), int> >\nF1 mix(F1 x, F1 y, F2 a)"
---
