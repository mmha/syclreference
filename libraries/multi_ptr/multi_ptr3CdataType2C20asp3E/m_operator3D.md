---
layout: method
title: operator=
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  multi_ptr<dataT, addressSpace> & operator=(cl::sycl::multi_ptr::pointer_t):
    arguments:
      - description: " New pointer that the object should manipulate"
        name: ptr
        type: cl::sycl::multi_ptr::pointer_t
    description: Assign a pointer to this object
    return: ""
    signature_with_names: multi_ptr<dataT, addressSpace> & operator=(cl::sycl::multi_ptr::pointer_t ptr)
  "template <typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace> & operator=(dataType *)":
    arguments:
      - description: " New pointer that the object should manipulate"
        name: ptr
        type: dataType *
    description: Assign a pointer to this object
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace> & operator=(dataType * ptr)"
---
