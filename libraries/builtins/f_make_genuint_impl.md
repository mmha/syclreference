---
layout: function
title: make_genuint_impl
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I, detail::enable_if_t<((std::is_integral<I>::value)), int> >\nmake_unsigned_t<I> make_genuint_impl(I)":
    arguments:
      - description: ""
        name: unnamed-0
        type: I
        unnamed: true
    description: ""
    return: ""
    signature_with_names: "template <typename I, detail::enable_if_t<((std::is_integral<I>::value)), int> >\nmake_unsigned_t<I> make_genuint_impl(I)"
  "template <typename I, int N, detail::enable_if_t<((std::is_integral<I>::value)), int> >\nvec<make_unsigned_t<I>, N> make_genuint_impl(vec<I, N>)":
    arguments:
      - description: ""
        name: unnamed-0
        type: vec<I, N>
        unnamed: true
    description: ""
    return: ""
    signature_with_names: "template <typename I, int N, detail::enable_if_t<((std::is_integral<I>::value)), int> >\nvec<make_unsigned_t<I>, N> make_genuint_impl(vec<I, N>)"
---
