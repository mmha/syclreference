---
layout: function
title: fast_length
owner: __MISSING__
brief: "Returns the length of vector p computed as: `sqrt((half)(pow(p.x,2) + pow(p.y,2)+ ...))`."
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, typename return_t, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_gengeohalf<F>::value, detail::builtin::is_gengeofloat<F>::value>::value), int> >\nreturn_t fast_length(F)":
    arguments:
      - description: ""
        name: p
        type: F
    description: "Returns the length of vector p computed as: `sqrt((half)(pow(p.x,2) + pow(p.y,2)+ ...))`."
    return: ""
    signature_with_names: "template <typename F, typename return_t, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_gengeohalf<F>::value, detail::builtin::is_gengeofloat<F>::value>::value), int> >\nreturn_t fast_length(F p)"
---
