---
layout: method
title: device
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  device():
    description: Default Constructor. Constructs a device object in host mode.
    return: ""
    signature_with_names: device()
  device(cl::sycl::device &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::device &&
    description: Constructs a device object by moving another device object
    return: ""
    signature_with_names: device(cl::sycl::device && rhs)
  device(const cl::sycl::device &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::device &
    description: Constructs a device object from another device object and retains the cl_device_id object if the device is not in host mode.
    return: ""
    signature_with_names: device(const cl::sycl::device & rhs)
  explicit device(cl_device_id):
    arguments:
      - description: " A cl_device_id object."
        name: deviceID
        type: cl_device_id
    description: Constructs a device object using a cl_device_id object and retains the cl_device_id object if the device is not in host mode.
    return: ""
    signature_with_names: explicit device(cl_device_id deviceID)
  explicit device(const cl::sycl::ddevice_shptr &):
    arguments:
      - description: ""
        name: impl
        type: const cl::sycl::ddevice_shptr &
    description: Constructs a device using an existing implementation object.
    return: ""
    signature_with_names: explicit device(const cl::sycl::ddevice_shptr & impl)
  explicit device(const cl::sycl::device_selector &):
    arguments:
      - description: " the device selector that will provide a device to"
        name: deviceSelector
        type: const cl::sycl::device_selector &
    description: Constructs a device using the requested device selector
    return: ""
    signature_with_names: explicit device(const cl::sycl::device_selector & deviceSelector)
---
