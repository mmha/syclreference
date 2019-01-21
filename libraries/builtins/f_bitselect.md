---
layout: function
title: bitselect
owner: __MISSING__
brief: Each bit of the result is the corresponding bit of a if the corresponding bit of c is 0.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T, detail::enable_if_t<(detail::builtin::is_gentype<T>::value), int> >\nT bitselect(T, T, T)":
    arguments:
      - description: ""
        name: a
        type: T
      - description: ""
        name: b
        type: T
      - description: ""
        name: c
        type: T
    description: Each bit of the result is the corresponding bit of a if the corresponding bit of c is 0.
    return: ""
    signature_with_names: "template <typename T, detail::enable_if_t<(detail::builtin::is_gentype<T>::value), int> >\nT bitselect(T a, T b, T c)"
---
