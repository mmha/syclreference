---
layout: function
title: length
owner: __MISSING__
brief: Return the length of vector p, i.e. `sqrt((p.x * p.x) + (p.y * p.y) + ...)`
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_gen_geo_anyfloat<F>::value), int> >\nreturn_t length(F)":
    arguments:
      - description: ""
        name: p
        type: F
    description: Return the length of vector p, i.e. `sqrt((p.x * p.x) + (p.y * p.y) + ...)`
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(detail::builtin::is_gen_geo_anyfloat<F>::value), int> >\nreturn_t length(F p)"
---
