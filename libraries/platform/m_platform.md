---
layout: method
title: platform
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit platform(cl_platform_id):
    arguments:
      - description: " The cl_platform_id object constructed using the OpenCL"
        name: platformID
        type: cl_platform_id
    description: Constructs a platform object using a cl_platform_id object.
    return: ""
    signature_with_names: explicit platform(cl_platform_id platformID)
  explicit platform(const cl::sycl::device_selector &):
    arguments:
      - description: " User device selector"
        name: deviceSelector
        type: const cl::sycl::device_selector &
    description: Constructs a platform from an existing device selector
    return: ""
    signature_with_names: explicit platform(const cl::sycl::device_selector & deviceSelector)
  explicit platform(const cl::sycl::dplatform_shptr &):
    arguments:
      - description: ""
        name: impl
        type: const cl::sycl::dplatform_shptr &
    description: Constructs a platform from a shared a pointer
    return: ""
    signature_with_names: explicit platform(const cl::sycl::dplatform_shptr & impl)
  platform():
    description: Default Constructor. Constructs a platform object in host mode.
    return: ""
    signature_with_names: platform()
  platform(const cl::sycl::platform &):
    annotation:
      - default
    arguments:
      - description: " The platform object to copy"
        name: rhs
        type: const cl::sycl::platform &
    description: Copy Constructor. Constructs a platform object from another platform object.
    return: ""
    signature_with_names: platform(const cl::sycl::platform & rhs)
---
