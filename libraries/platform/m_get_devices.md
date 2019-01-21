---
layout: method
title: get_devices
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  vector_class<cl::sycl::device> get_devices(info::device_type) const:
    arguments:
      - description: " The type of devices to search for, set to"
        name: deviceType
        type: info::device_type
    description: Get a list of devices associated with the platform.
    return: " A vector of device objects."
    signature_with_names: vector_class<cl::sycl::device> get_devices(info::device_type deviceType) const
---
