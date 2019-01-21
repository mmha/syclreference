---
layout: method
title: multi_ptr<dataT, addressSpace>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  multi_ptr<dataT, addressSpace>():
    annotation:
      - default
    description: Default constructor
    return: ""
    signature_with_names: multi_ptr<dataT, addressSpace>()
  multi_ptr<dataT, addressSpace>(cl::sycl::multi_ptr::pointer_t):
    arguments:
      - description: " Pointer that the class should manipulate."
        name: ptr
        type: cl::sycl::multi_ptr::pointer_t
    description: Initialize the object using the given pointer.
    return: ""
    signature_with_names: multi_ptr<dataT, addressSpace>(cl::sycl::multi_ptr::pointer_t ptr)
  "template <int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace>(cl::sycl::accessor<dataType, dimensions, Mode, detail::address_space_trait<dataType, asp>::target, isPlaceholder>)":
    arguments:
      - description: " Accessor to retrieve the pointer from"
        name: acc
        type: cl::sycl::accessor<dataType, dimensions, Mode, detail::address_space_trait<dataType, asp>::target, isPlaceholder>
    description: Initialize the object using an accessor
    return: ""
    signature_with_names: "template <int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace>(cl::sycl::accessor<dataType, dimensions, Mode, detail::address_space_trait<dataType, asp>::target, isPlaceholder> acc)"
  "template <typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace>(dataType *)":
    arguments:
      - description: " Pointer that is not address space qualified"
        name: ptr
        type: dataType *
    description: Initialize the object using the given non address space qualified pointer.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nmulti_ptr<dataT, addressSpace>(dataType * ptr)"
---
