---
layout: class
title: stream_vec<kVecPart, kEnabled, elementT, kDimensions>
owner: __MISSING__
brief: Template struct that contains a function call operator that streams a vec object to a stream object. Class is specialized for each combination of kVecPart specifying the part of a vector to stream and kEnabled specifying whether it streamed or not. This is the default template that does nothing.
tags:
  - class
defined-in-file: ""
declaration: "template <int kVecPart, bool kEnabled, typename elementT, int kDimensions>\nstruct cl::sycl::stream_vec;"
ctor: unspecified
dtor: unspecified
namespace:
  - cl
  - sycl
---
