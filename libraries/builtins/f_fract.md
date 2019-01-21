---
layout: function
title: fract
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename F, access::address_space AddressSpace, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF fract(F, detail::builtin_ptr<F, AddressSpace>)":
    arguments:
      - description: ""
        name: x
        type: F
      - description: ""
        name: iptr
        type: detail::builtin_ptr<F, AddressSpace>
    description: Returns `fmin(x - floor (x), 0x1.fffffep-1f)`. `floor(x)` is returned in iptr.
    return: ""
    signature_with_names: "template <typename F, access::address_space AddressSpace, detail::enable_if_t<(detail::builtin::is_genfloat<F>::value), int> >\nF fract(F x, detail::builtin_ptr<F, AddressSpace> iptr)"
---
