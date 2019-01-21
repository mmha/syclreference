---
layout: function
title: fast_distance
owner: __MISSING__
brief: Returns f ast `length(p0 - p1)`.
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F1, typename F2, typename F, detail::enable_if_t<((computecpp::gsl::or_<detail::builtin::is_gengeohalf<F1>::value, detail::builtin::is_gengeofloat<F1>::value>::value) && (computecpp::gsl::or_<detail::builtin::is_gengeohalf<F2>::value, detail::builtin::is_gengeofloat<F2>::value>::value)), int> >\nF fast_distance(F1, F2)":
    arguments:
      - description: ""
        name: p0
        type: F1
      - description: ""
        name: p1
        type: F2
    description: Returns f ast `length(p0 - p1)`.
    return: ""
    signature_with_names: "template <typename F1, typename F2, typename F, detail::enable_if_t<((computecpp::gsl::or_<detail::builtin::is_gengeohalf<F1>::value, detail::builtin::is_gengeofloat<F1>::value>::value) && (computecpp::gsl::or_<detail::builtin::is_gengeohalf<F2>::value, detail::builtin::is_gengeofloat<F2>::value>::value)), int> >\nF fast_distance(F1 p0, F2 p1)"
---
