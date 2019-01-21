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
  explicit id(const detail::index_array_operators<2, cl::sycl::id> &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array_operators<2, cl::sycl::id> &
    description: copy constructor from the templated operator interface class used internally to the public templated class.
    return: ""
    signature_with_names: explicit id(const detail::index_array_operators<2, cl::sycl::id> & indexArray)
  explicit id(const item<2> &):
    arguments:
      - description: ""
        name: itemBase
        type: const item<2> &
    description: copy constructor from the non templated base class used internally to the public templated class.
    return: ""
    signature_with_names: explicit id(const item<2> & itemBase)
  id():
    description: Default constructor for id, initialized to { 0, 0, 0 }
    return: ""
    signature_with_names: id()
  id(const cl::sycl::id<2> &):
    annotation:
      - default
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::id<2> &
    description: Default copy constructor for id.
    return: ""
    signature_with_names: id(const cl::sycl::id<2> & rhs)
  id(const detail::index_array &):
    arguments:
      - description: ""
        name: indexArray
        type: const detail::index_array &
    description: copy constructor from the non templated base class used internally to the public templated class.
    return: ""
    signature_with_names: id(const detail::index_array & indexArray)
  id(const detail::index_array_operators<2, range> &):
    arguments:
      - description: ""
        name: r
        type: const detail::index_array_operators<2, range> &
    description: meant for internal use (conversion for operators).
    return: ""
    signature_with_names: id(const detail::index_array_operators<2, range> & r)
  id(const detail::item_base &):
    arguments:
      - description: ""
        name: itemBase
        type: const detail::item_base &
    description: Constructor taking in a item
    return: ""
    signature_with_names: id(const detail::item_base & itemBase)
  id(const range<2> &):
    arguments:
      - description: ""
        name: r
        type: const range<2> &
    description: conversion from range to id constructor.
    return: ""
    signature_with_names: id(const range<2> & r)
  id(size_t, size_t):
    arguments:
      - description: ""
        name: x
        type: size_t
      - description: ""
        name: y
        type: size_t
    description: Create a two dimensional id from two size_t parameters.
    return: ""
    signature_with_names: id(size_t x, size_t y)
---
