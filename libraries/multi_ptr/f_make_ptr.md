---
layout: function
title: make_ptr
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename dataType, cl::sycl::access::address_space Space>\nmulti_ptr<dataType, Space> make_ptr(typename multi_ptr<dataType, Space>::pointer_t)":
    arguments:
      - description: ""
        name: ptr
        type: typename multi_ptr<dataType, Space>::pointer_t
    description: ""
    return: ""
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space Space>\nmulti_ptr<dataType, Space> make_ptr(typename multi_ptr<dataType, Space>::pointer_t ptr)"
  "template <typename dataType, cl::sycl::access::address_space Space>\ntypename std::enable_if<!std::is_same<typename multi_ptr<dataType, Space>::pointer_t, dataType *>::value, multi_ptr<dataType, Space>>::type make_ptr(dataType *)":
    arguments:
      - description: " The raw pointer from which to create the multi_ptr."
        name: ptr
        type: dataType *
    description: Create a multi_ptr object from a raw pointer.
    return: " A multi_ptr object pointing to the same address pointed as by ptr."
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space Space>\ntypename std::enable_if<!std::is_same<typename multi_ptr<dataType, Space>::pointer_t, dataType *>::value, multi_ptr<dataType, Space>>::type make_ptr(dataType * ptr)"
---
