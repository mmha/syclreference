---
layout: method
title: multi_ptr<void, asp>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  multi_ptr<void, asp>():
    annotation:
      - default
    description: Default constructor
    return: ""
    signature_with_names: multi_ptr<void, asp>()
  multi_ptr<void, asp>(cl::sycl::multi_ptr<void, asp>::pointer_t):
    arguments:
      - description: " Pointer that the class should manipulate."
        name: ptr
        type: cl::sycl::multi_ptr<void, asp>::pointer_t
    description: Initialize the object using the given pointer.
    return: ""
    signature_with_names: multi_ptr<void, asp>(cl::sycl::multi_ptr<void, asp>::pointer_t ptr)
  "template <int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<void, asp>(cl::sycl::accessor<void, dimensions, Mode, detail::address_space_trait<void, asp>::target, isPlaceholder>)":
    arguments:
      - description: " Accessor to retrieve the pointer from"
        name: acc
        type: cl::sycl::accessor<void, dimensions, Mode, detail::address_space_trait<void, asp>::target, isPlaceholder>
    description: Initialize the object using an accessor
    return: ""
    signature_with_names: "template <int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<void, asp>(cl::sycl::accessor<void, dimensions, Mode, detail::address_space_trait<void, asp>::target, isPlaceholder> acc)"
  "template <typename ElementType, int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<void, asp>(accessor<ElementType, dimensions, Mode, detail::address_space_trait<ElementType, asp>::target, isPlaceholder>)":
    arguments:
      - description: " Accessor to retrieve the pointer from"
        name: acc
        type: accessor<ElementType, dimensions, Mode, detail::address_space_trait<ElementType, asp>::target, isPlaceholder>
    description: Initialize the object using an accessor
    return: ""
    signature_with_names: "template <typename ElementType, int dimensions, access::mode Mode, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nmulti_ptr<void, asp>(accessor<ElementType, dimensions, Mode, detail::address_space_trait<ElementType, asp>::target, isPlaceholder> acc)"
  "template <typename ElementType, typename overloadDependantT, typename >\nexplicit multi_ptr<void, asp>(const multi_ptr<ElementType, asp> &)":
    arguments:
      - description: " Pointer to convert to multi_ptr"
        name: ptr
        type: const multi_ptr<ElementType, asp> &
    description: Explicit conversion from a multi_ptr<ElementType>
    return: ""
    signature_with_names: "template <typename ElementType, typename overloadDependantT, typename >\nexplicit multi_ptr<void, asp>(const multi_ptr<ElementType, asp> & ptr)"
  "template <typename overloadDependantT, typename >\nmulti_ptr<void, asp>(void *)":
    arguments:
      - description: " Pointer that is not address space qualified"
        name: ptr
        type: void *
    description: Initialize the object using the given non address space qualified pointer.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nmulti_ptr<void, asp>(void * ptr)"
---
