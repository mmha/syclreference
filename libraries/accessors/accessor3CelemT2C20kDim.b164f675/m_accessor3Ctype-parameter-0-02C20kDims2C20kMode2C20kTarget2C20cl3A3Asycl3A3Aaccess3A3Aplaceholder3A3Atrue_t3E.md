---
layout: method
title: accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>():
    description: Constructs a default placeholder accessor without associated storage.
    return: ""
    signature_with_names: accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>()
  accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> &, cl::sycl::handler &):
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs a placeholder accessor of access target access::target::global_buffer or access::target::constant_buffer by taking a buffer object and a handler and initialises the base_accessor with the buffer, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> & bufferRef, cl::sycl::handler & commandHandler)
  accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> &, cl::sycl::handler &, range<kDims>, id<kDims>):
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
      - description: " the offset and range that this accessor can access."
        name: accessRange
        type: range<kDims>
      - description: ""
        name: accessOffset
        type: id<kDims>
    description: Constructs a ranged placeholder accessor
    return: ""
    signature_with_names: accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> & bufferRef, cl::sycl::handler & commandHandler, range<kDims> accessRange, id<kDims> accessOffset)
  accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> &, range<kDims>, id<kDims>):
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims> &
      - description: " the offset and range that this accessor can access."
        name: accessRange
        type: range<kDims>
      - description: ""
        name: accessOffset
        type: id<kDims>
    description: Constructs a ranged placeholder accessor
    return: ""
    signature_with_names: accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims> & bufferRef, range<kDims> accessRange, id<kDims> accessOffset)
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, 1, AllocatorT> &, cl::sycl::handler &)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, 1, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs a placeholder 0 dimentional accessor of access target access::target::global_buffer or access::target::constant_buffer by taking a buffer object and a handler and initialises the base_accessor with the buffer, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, 1, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler)"
  "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> &, cl::sycl::handler &)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs a placeholder accessor of access target access::target::global_buffer or access::target::constant_buffer by taking a buffer object and a handler and initialises the base_accessor with the buffer, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler)"
  "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> &, cl::sycl::handler &, range<kDims>, id<kDims>)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
      - description: " the offset and range that this accessor can access."
        name: accessRange
        type: range<kDims>
      - description: ""
        name: accessOffset
        type: id<kDims>
    description: Constructs a ranged placeholder accessor
    return: ""
    signature_with_names: "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler, range<kDims> accessRange, id<kDims> accessOffset)"
  "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> &, id<kDims>, range<kDims>)":
    annotation:
      - deprecated (Deprecated constructor since SYCL 1.2.1)
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: ""
        name: accessOffset
        type: id<kDims>
      - description: " the offset and range that this accessor can access."
        name: accessRange
        type: range<kDims>
    description: Constructs a ranged placeholder accessor
    return: ""
    signature_with_names: "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> & bufferRef, id<kDims> accessOffset, range<kDims> accessRange)"
  "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> &, range<kDims>, id<kDims>)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " the offset and range that this accessor can access."
        name: accessRange
        type: range<kDims>
      - description: ""
        name: accessOffset
        type: id<kDims>
    description: Constructs a ranged placeholder accessor
    return: ""
    signature_with_names: "template <typename AllocatorT>\naccessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, kDims, AllocatorT> & bufferRef, range<kDims> accessRange, id<kDims> accessOffset)"
  "template <typename AllocatorT>\nexplicit accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, interface_dims, AllocatorT> &)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, interface_dims, AllocatorT> &
    description: Constructs a placeholder accessor
    return: ""
    signature_with_names: "template <typename AllocatorT>\nexplicit accessor<type-parameter-0-0, kDims, kMode, kTarget, cl::sycl::access::placeholder::true_t>(buffer<elemT, interface_dims, AllocatorT> & bufferRef)"
---
