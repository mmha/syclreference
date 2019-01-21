---
layout: class
title: pitch_range<kDimensions>
owner: __MISSING__
brief: Helper struct to construct a range used for an image pitch, which uses one dimension less than the image it's used in
tags:
  - class
defined-in-file: ""
declaration: "template <int kDimensions>\nstruct cl::sycl::detail::pitch_range;"
ctor: unspecified
dtor: unspecified
typedefs:
  type:
    definition: range<kDimensions - 1>
    description: In the general case, just use a range of one dimension one less
namespace:
  - cl
  - sycl
  - detail
---
