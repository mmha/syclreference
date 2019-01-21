---
layout: function
title: nan
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_ugenint<I>::value, detail::builtin::is_ugenlonginteger<I>::value>::value), int> >\nauto nan(I) -> detail::matching_float_t<I>":
    arguments:
      - description: ""
        name: nancode
        type: I
    description: Returns x if |x| < |y|, y if |y| < |x|, otherwise `fmin(x, y)`.
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_ugenint<I>::value, detail::builtin::is_ugenlonginteger<I>::value>::value), int> >\nauto nan(I nancode) -> detail::matching_float_t<I>"
  "template <typename I, detail::enable_if_t<(detail::builtin::is_ushortn<I>::value), int> >\ndetail::matching_float_t<I> nan(I)":
    arguments:
      - description: ""
        name: nancode
        type: I
    description: ""
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<(detail::builtin::is_ushortn<I>::value), int> >\ndetail::matching_float_t<I> nan(I nancode)"
---
