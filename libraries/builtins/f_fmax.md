---
layout: function
title: fmax
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F1>::value && (detail::builtin::is_genfloat<F2>::value || detail::builtin::is_sgenfloat<F2, detail::scalar_t<F>>::value)), int> >\nF fmax(F1, F2)":
    arguments:
      - description: ""
        name: x
        type: F1
      - description: ""
        name: y
        type: F2
    description: Returns y if `x < y`, otherwise it returns x.
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F, detail::enable_if_t<(detail::builtin::is_genfloat<F1>::value && (detail::builtin::is_genfloat<F2>::value || detail::builtin::is_sgenfloat<F2, detail::scalar_t<F>>::value)), int> >\nF fmax(F1 x, F2 y)"
---
