---
layout: function
title: sycl_to_abacus
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  constexpr abacus::sycl_to_abacus_t<int> sycl_to_abacus(const int &):
    arguments:
      - description: ""
        name: t
        type: const int &
    description: Converts a SYCL type to the corresponding Abacus type.
    return: " The Abacus equivalent of t."
    signature_with_names: constexpr abacus::sycl_to_abacus_t<int> sycl_to_abacus(const int & t)
  "template <int N>\nconstexpr abacus::sycl_to_abacus_t<cl::sycl::vec<cl::sycl::cl_float, N>> sycl_to_abacus(const cl::sycl::vec<cl::sycl::half, N> &)":
    arguments:
      - description: ""
        name: v
        type: const cl::sycl::vec<cl::sycl::half, N> &
    description: Converts a SYCL type to the corresponding Abacus type.
    return: " The Abacus equivalent of t."
    signature_with_names: "template <int N>\nconstexpr abacus::sycl_to_abacus_t<cl::sycl::vec<cl::sycl::cl_float, N>> sycl_to_abacus(const cl::sycl::vec<cl::sycl::half, N> & v)"
  "template <typename T, int N>\nabacus::sycl_to_abacus_t<cl::sycl::vec<T, N>> sycl_to_abacus(const cl::sycl::vec<T, N> &)":
    arguments:
      - description: ""
        name: v
        type: const cl::sycl::vec<T, N> &
    description: Converts a SYCL type to the corresponding Abacus type.
    return: " The Abacus equivalent of t."
    signature_with_names: "template <typename T, int N>\nabacus::sycl_to_abacus_t<cl::sycl::vec<T, N>> sycl_to_abacus(const cl::sycl::vec<T, N> & v)"
  "template <typename T>\nconstexpr abacus::sycl_to_abacus_t<T> * sycl_to_abacus(T *)":
    arguments:
      - description: ""
        name: p
        type: T *
    description: ""
    return: ""
    signature_with_names: "template <typename T>\nconstexpr abacus::sycl_to_abacus_t<T> * sycl_to_abacus(T * p)"
  "template <typename T>\nconstexpr abacus::sycl_to_abacus_t<T> sycl_to_abacus(const T &)":
    arguments:
      - description: ""
        name: t
        type: const T &
    description: Converts a SYCL type to the corresponding Abacus type.
    return: " The Abacus equivalent of t."
    signature_with_names: "template <typename T>\nconstexpr abacus::sycl_to_abacus_t<T> sycl_to_abacus(const T & t)"
---
