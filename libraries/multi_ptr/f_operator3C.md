---
layout: function
title: operator<
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(const cl::sycl::multi_ptr<dataType, Space> &, const cl::sycl::multi_ptr<dataType, Space> &)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::multi_ptr<dataType, Space> &
      - description: ""
        name: rhs
        type: const cl::sycl::multi_ptr<dataType, Space> &
    description: Less than operator.
    return: " True if the lhs parameter address is strictly less than rhs, false"
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(const cl::sycl::multi_ptr<dataType, Space> & lhs, const cl::sycl::multi_ptr<dataType, Space> & rhs)"
  "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(const cl::sycl::multi_ptr<dataType, Space> &, std::nullptr_t)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::multi_ptr<dataType, Space> &
      - description: ""
        name: rhs
        type: std::nullptr_t
    description: Less than operator.
    return: " True if the lhs parameter is strictly less than null."
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(const cl::sycl::multi_ptr<dataType, Space> & lhs, std::nullptr_t rhs)"
  "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(std::nullptr_t, const cl::sycl::multi_ptr<dataType, Space> &)":
    arguments:
      - description: ""
        name: lhs
        type: std::nullptr_t
      - description: ""
        name: rhs
        type: const cl::sycl::multi_ptr<dataType, Space> &
    description: Less than operator.
    return: " True if the rhs parameter is strictly greater than null."
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space Space>\nbool operator<(std::nullptr_t lhs, const cl::sycl::multi_ptr<dataType, Space> & rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::constant_ptr<dataType> &, const cl::sycl::constant_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::constant_ptr<dataType> &
      - description: ""
        name: rhs
        type: const cl::sycl::constant_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::constant_ptr<dataType> & lhs, const cl::sycl::constant_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::constant_ptr<dataType> &, std::nullptr_t)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::constant_ptr<dataType> &
      - description: ""
        name: rhs
        type: std::nullptr_t
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::constant_ptr<dataType> & lhs, std::nullptr_t rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::global_ptr<dataType> &, const cl::sycl::global_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::global_ptr<dataType> &
      - description: ""
        name: rhs
        type: const cl::sycl::global_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::global_ptr<dataType> & lhs, const cl::sycl::global_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::global_ptr<dataType> &, std::nullptr_t)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::global_ptr<dataType> &
      - description: ""
        name: rhs
        type: std::nullptr_t
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::global_ptr<dataType> & lhs, std::nullptr_t rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::local_ptr<dataType> &, const cl::sycl::local_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::local_ptr<dataType> &
      - description: ""
        name: rhs
        type: const cl::sycl::local_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::local_ptr<dataType> & lhs, const cl::sycl::local_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::local_ptr<dataType> &, std::nullptr_t)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::local_ptr<dataType> &
      - description: ""
        name: rhs
        type: std::nullptr_t
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::local_ptr<dataType> & lhs, std::nullptr_t rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::private_ptr<dataType> &, const cl::sycl::private_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::private_ptr<dataType> &
      - description: ""
        name: rhs
        type: const cl::sycl::private_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::private_ptr<dataType> & lhs, const cl::sycl::private_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(const cl::sycl::private_ptr<dataType> &, std::nullptr_t)":
    arguments:
      - description: ""
        name: lhs
        type: const cl::sycl::private_ptr<dataType> &
      - description: ""
        name: rhs
        type: std::nullptr_t
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(const cl::sycl::private_ptr<dataType> & lhs, std::nullptr_t rhs)"
  "template <typename dataType>\nbool operator<(std::nullptr_t, const cl::sycl::constant_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: std::nullptr_t
      - description: ""
        name: rhs
        type: const cl::sycl::constant_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(std::nullptr_t lhs, const cl::sycl::constant_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(std::nullptr_t, const cl::sycl::global_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: std::nullptr_t
      - description: ""
        name: rhs
        type: const cl::sycl::global_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(std::nullptr_t lhs, const cl::sycl::global_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(std::nullptr_t, const cl::sycl::local_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: std::nullptr_t
      - description: ""
        name: rhs
        type: const cl::sycl::local_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(std::nullptr_t lhs, const cl::sycl::local_ptr<dataType> & rhs)"
  "template <typename dataType>\nbool operator<(std::nullptr_t, const cl::sycl::private_ptr<dataType> &)":
    arguments:
      - description: ""
        name: lhs
        type: std::nullptr_t
      - description: ""
        name: rhs
        type: const cl::sycl::private_ptr<dataType> &
    description: ""
    return: ""
    signature_with_names: "template <typename dataType>\nbool operator<(std::nullptr_t lhs, const cl::sycl::private_ptr<dataType> & rhs)"
---
