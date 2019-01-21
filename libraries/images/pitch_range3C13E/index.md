---
layout: class
title: pitch_range<1>
owner: __MISSING__
brief: Specialization of the pitch range for 1-dimensional images
tags:
  - class
defined-in-file: ""
declaration: "\nstruct cl::sycl::detail::pitch_range;"
ctor: unspecified
dtor: unspecified
typedefs:
  type:
    definition: std::integral_constant<int, 1>
    description: This can be any valid type, as long as it's not a range<0>, and pitch should be SFINAE-d out anyway for 1D images
namespace:
  - cl
  - sycl
  - detail
---
