---
layout: method
title: set_args
owner: __MISSING__
brief: Set all the given kernel args arguments for an OpenCL kernel, as if set_arg() was used with each of them in the same order and increasing index always starting at 0.
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename... Ts>\nvoid set_args(Ts &&...)":
    arguments:
      - description: " Parameters passed to the OpenCL kernel"
        name: args
        type: Ts &&...
    description: Set all the given kernel args arguments for an OpenCL kernel, as if set_arg() was used with each of them in the same order and increasing index always starting at 0.
    return: ""
    signature_with_names: "template <typename... Ts>\nvoid set_args(Ts &&... args)"
---
