---
layout: function
title: cross
owner: __MISSING__
brief: Returns the cross product of p0.xyz and p1.xyz.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, int N, detail::enable_if_t<((detail::is_custom_half_type<F>::value || std::is_same<F, float>::value || std::is_same<F, double>::value) && (N == 3 || N == 4)), int> >\nvec<F, N> cross(const vec<F, N>, const vec<F, N>)":
    arguments:
      - description: ""
        name: p0
        type: const vec<F, N>
      - description: ""
        name: p1
        type: const vec<F, N>
    description: Returns the cross product of p0.xyz and p1.xyz.
    return: ""
    signature_with_names: "template <typename F, int N, detail::enable_if_t<((detail::is_custom_half_type<F>::value || std::is_same<F, float>::value || std::is_same<F, double>::value) && (N == 3 || N == 4)), int> >\nvec<F, N> cross(const vec<F, N> p0, const vec<F, N> p1)"
---
