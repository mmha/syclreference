---
layout: method
title: accessor<elemT, kDims, kMode, kTarget, isPlaceholder>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, interface_dims, AllocatorT> &)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, interface_dims, AllocatorT> &
    description: Constructs an accessor of access target access::target::host_buffer by taking a buffer object and initialises the base_accessor with the buffer, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, interface_dims, AllocatorT> & bufferRef)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, interface_dims, AllocatorT> &, cl::sycl::handler &)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, interface_dims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs an accessor of access target access::target::global_buffer or access::target::constant_buffer by taking a buffer object and a handler and initialises the base_accessor with the buffer, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, interface_dims, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> &, cl::sycl::handler &, id<kDims>, range<kDims>)":
    annotation:
      - deprecated (Deprecated constructor since SYCL 1.2.1)
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
      - description: " The offset that the sub accessor should have access from."
        name: accessOffset
        type: id<kDims>
      - description: " The range that the sub accessor should have access to."
        name: accessRange
        type: range<kDims>
    description: Constructs an accessor of access target access::target::global_buffer or access::target::constant_buffer by taking a buffer object, a handler, an offset and a range and initialises the base_accessor with the buffer, the handler, the access target, the access mode and the element size. This constructor is for constructing a sub accessor.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler, id<kDims> accessOffset, range<kDims> accessRange)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> &, cl::sycl::handler &, range<kDims>, id<kDims>)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
      - description: " The range that the accessor should have access to"
        name: accessRange
        type: range<kDims>
      - description: " The offset that the accessor should have access from"
        name: accessOffset
        type: id<kDims>
    description: Constructs an accessor of access target global_buffer or constant_buffer from a buffer object, a handler, a range and an offset.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> & bufferRef, cl::sycl::handler & commandHandler, range<kDims> accessRange, id<kDims> accessOffset)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> &, id<kDims>, range<kDims>)":
    annotation:
      - deprecated (Deprecated constructor since SYCL 1.2.1)
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " The offset that the sub accessor should have access from."
        name: accessOffset
        type: id<kDims>
      - description: " The range that the sub accessor should have access to."
        name: accessRange
        type: range<kDims>
    description: Constructs an accessor of access target access::target::host_buffer by taking a buffer object, an offset and a range and initialises the base_accessor with the buffer, the access target, the access mode and the element size. This constructor is for constructing a sub accessor.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> & bufferRef, id<kDims> accessOffset, range<kDims> accessRange)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> &, range<kDims>, id<kDims>)":
    arguments:
      - description: " Reference to the buffer object the accessor is to access"
        name: bufferRef
        type: buffer<elemT, kDims, AllocatorT> &
      - description: " The range that the accessor should have access to"
        name: accessRange
        type: range<kDims>
      - description: " The offset that the accessor should have access from"
        name: accessOffset
        type: id<kDims>
    description: Constructs an accessor of access target host_buffer from a buffer object, an offset and a range
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(buffer<elemT, kDims, AllocatorT> & bufferRef, range<kDims> accessRange, id<kDims> accessOffset)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<(kDims + 1), AllocatorT> &, cl::sycl::handler &)":
    arguments:
      - description: " Reference to the image object being accessed."
        name: imageRef
        type: image<(kDims + 1), AllocatorT> &
      - description: " Reference to the handler of the command group the"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs an accessor of access target access::target::image_array by taking an image object of dimensionality one greater than this accessor and initialises the accessor_common with the image.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<(kDims + 1), AllocatorT> & imageRef, cl::sycl::handler & commandHandler)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<kDims, AllocatorT> &, cl::sycl::handler &)":
    arguments:
      - description: " Reference to the image object the accessor is to access"
        name: imageRef
        type: image<kDims, AllocatorT> &
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs an accessor of access target access::target::image by taking an image object and a handler and initialises the base_accessor with the image, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<kDims, AllocatorT> & imageRef, cl::sycl::handler & commandHandler)"
  "template <typename AllocatorT, typename overloadDependantT, typename >\nexplicit accessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<kDims, AllocatorT> &)":
    arguments:
      - description: " Reference to the image object the accessor is to access"
        name: imageRef
        type: image<kDims, AllocatorT> &
    description: Constructs an accessor of access target access::target::host_image by taking an image object and initialises the base_accessor with the image, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename AllocatorT, typename overloadDependantT, typename >\nexplicit accessor<elemT, kDims, kMode, kTarget, isPlaceholder>(image<kDims, AllocatorT> & imageRef)"
  "template <typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(cl::sycl::handler &)":
    arguments:
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs a 0-dimensional accessor of access target access::target::local by taking a handler and initialises the base_accessor with a range of 1, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(cl::sycl::handler & commandHandler)"
  "template <typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(range<interface_dims>, cl::sycl::handler &)":
    arguments:
      - description: " The range that local memory should be allocated for."
        name: numElements
        type: range<interface_dims>
      - description: " Reference to the handler object for the command group"
        name: commandHandler
        type: cl::sycl::handler &
    description: Constructs an n-dimensional accessor of access target access::target::local by taking a range and a handler and initialises the base_accessor with the range, the handler, the access target, the access mode and the element size.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\naccessor<elemT, kDims, kMode, kTarget, isPlaceholder>(range<interface_dims> numElements, cl::sycl::handler & commandHandler)"
---
