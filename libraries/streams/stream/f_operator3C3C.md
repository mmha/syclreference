---
layout: function
title: operator<<
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  std::ostream & operator<<(std::ostream &, const cl::sycl::stream &):
    arguments:
      - description: ""
        name: out
        type: std::ostream &
      - description: ""
        name: rhs
        type: const cl::sycl::stream &
    description: Friend function declaration to give global stream operator access to private members.
    return: ""
    signature_with_names: std::ostream & operator<<(std::ostream & out, const cl::sycl::stream & rhs)
  "template <typename elementT, int kDimensions, int... swizzleIndexes>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream &, const swizzled_vec<elementT, kDimensions, swizzleIndexes...>)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " The swizzled_vec object to be streamed"
        name: rhs
        type: const swizzled_vec<elementT, kDimensions, swizzleIndexes...>
    description: Streams a swizzled_vec object to a stream object
    return: " Original stream object"
    signature_with_names: "template <typename elementT, int kDimensions, int... swizzleIndexes>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream & os, const swizzled_vec<elementT, kDimensions, swizzleIndexes...> rhs)"
  "template <typename elementT, int kDimensions>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream &, const vec<elementT, kDimensions>)":
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The vec object to be streamed."
        name: rhs
        type: const vec<elementT, kDimensions>
    description: Template stream operator that streams a vec object to a stream object.
    return: ""
    signature_with_names: "template <typename elementT, int kDimensions>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream & os, const vec<elementT, kDimensions> rhs)"
  "template <typename valueT>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream &, valueT)":
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The value to be streamed."
        name: rhs
        type: valueT
    description: Template stream operator that streams a value to a stream object.
    return: ""
    signature_with_names: "template <typename valueT>\nconst cl::sycl::stream & operator<<(const cl::sycl::stream & os, valueT rhs)"
---
