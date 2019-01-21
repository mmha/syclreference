---
layout: class
title: hash<cl::sycl::sampler>
owner: __MISSING__
brief: provides a specialization for std::hash for the buffer class. An std::hash<std::shared_ptr<...>> object is created and its function call operator is used to hash the contents of the shared_ptr. The returned hash is actually the result of (size_t) object.get_impl().get()
tags:
  - class
defined-in-file: ""
declaration: "\nstruct std::hash;"
ctor: unspecified
dtor: unspecified
namespace:
  - std
---
