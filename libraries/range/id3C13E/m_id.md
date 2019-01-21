---
layout: method
title: id
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit id(const detail::index_array_operators<1, cl::sycl::id> &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array_operators<1, cl::sycl::id> &
    description: copy constructor from the templated operator interface class used internally to the public templated class.
    return: ""
    signature_with_names: explicit id(const detail::index_array_operators<1, cl::sycl::id> & indexArray)
  explicit id(const item<1> &):
    arguments:
      - description: ""
        name: it
        type: const item<1> &
    description: copy constructor from the non templated base class used internally to the public templated class.
    return: ""
    signature_with_names: explicit id(const item<1> & it)
  id():
    description: Default constructor for id, initialized to { 0, 0, 0 }
    return: ""
    signature_with_names: id()
  id(const cl::sycl::id<1> &):
    annotation:
      - default
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::id<1> &
    description: Default copy constructor for id.
    return: ""
    signature_with_names: id(const cl::sycl::id<1> & rhs)
  id(const detail::index_array &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array &
    description: copy constructor from the non templated base class used internally to the public templated class.
    return: ""
    signature_with_names: id(const detail::index_array & indexArray)
  id(const detail::item_base &):
    arguments:
      - description: ""
        name: itemBase
        type: const detail::item_base &
    description: Constructor taking in a item
    return: ""
    signature_with_names: id(const detail::item_base & itemBase)
  id(const range<1> &):
    arguments:
      - description: ""
        name: r
        type: const range<1> &
    description: conversion from range to id constructor.
    return: ""
    signature_with_names: id(const range<1> & r)
  id(size_t):
    arguments:
      - description: ""
        name: x
        type: size_t
    description: Create a one dimensional id from a single size_t parameter.
    return: ""
    signature_with_names: id(size_t x)
---
