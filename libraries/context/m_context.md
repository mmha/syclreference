---
layout: method
title: context
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  context(cl::sycl::context &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::context &&
    description: Constructs a context object by moving another device object.
    return: ""
    signature_with_names: context(cl::sycl::context && rhs)
  context(cl_context, cl::sycl::async_handler):
    arguments:
      - description: " A cl_context object."
        name: context
        type: cl_context
      - description: ""
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object using a cl_context object.
    return: ""
    signature_with_names: context(cl_context context, cl::sycl::async_handler asyncHandler)
  context(const cl::sycl::context &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::context &
    description: Constructs a context object from another device object and retains the cl_context object if the context is not in host mode.
    return: ""
    signature_with_names: context(const cl::sycl::context & rhs)
  context(const cl::sycl::device &, cl::sycl::async_handler):
    arguments:
      - description: ""
        name: dev
        type: const cl::sycl::device &
      - description: " An optional parameter to specify the async_handler"
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object using a device object. The context is constructed with the device object provided.
    return: ""
    signature_with_names: context(const cl::sycl::device & dev, cl::sycl::async_handler asyncHandler)
  context(const cl::sycl::device_selector &, info::gl_context_interop, cl::sycl::async_handler):
    annotation:
      - deprecated (Context constructor is deprecated)
    arguments:
      - description: " A reference to a device_selector object."
        name: deviceSelector
        type: const cl::sycl::device_selector &
      - description: " Specify whether to use the context for OpenGL interop."
        name: interopFlag
        type: info::gl_context_interop
      - description: " An optional parameter to specify the async_handler"
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object using a device_selector object. The context is constructed with a single device retrieved from the device_selector object provided.
    return: ""
    signature_with_names: context(const cl::sycl::device_selector & deviceSelector, info::gl_context_interop interopFlag, cl::sycl::async_handler asyncHandler)
  context(const cl::sycl::platform &, cl::sycl::async_handler):
    arguments:
      - description: ""
        name: plt
        type: const cl::sycl::platform &
      - description: " An optional parameter to specify the async_handler"
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object using a platform object. The context is constructed with all the devices available under the platform object provided.
    return: ""
    signature_with_names: context(const cl::sycl::platform & plt, cl::sycl::async_handler asyncHandler)
  context(vector_class<cl::sycl::device>, cl::sycl::async_handler):
    arguments:
      - description: " A vector_class of device objects."
        name: deviceList
        type: vector_class<cl::sycl::device>
      - description: " An optional parameter to specify the async_handler"
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object using a vector_class of device objects. The context is constructed with the devices provided.
    return: ""
    signature_with_names: context(vector_class<cl::sycl::device> deviceList, cl::sycl::async_handler asyncHandler)
  explicit context(cl::sycl::async_handler):
    arguments:
      - description: ""
        name: asyncHandler
        type: cl::sycl::async_handler
    description: Constructs a context object in host mode.
    return: ""
    signature_with_names: explicit context(cl::sycl::async_handler asyncHandler)
  explicit context(cl::sycl::dcontext_shptr):
    arguments:
      - description: ""
        name: detail
        type: cl::sycl::dcontext_shptr
    description: ""
    return: ""
    signature_with_names: explicit context(cl::sycl::dcontext_shptr detail)
  explicit context(cl::sycl::detail::context *):
    arguments:
      - description: ""
        name: detail
        type: cl::sycl::detail::context *
    description: ""
    return: ""
    signature_with_names: explicit context(cl::sycl::detail::context * detail)
---
