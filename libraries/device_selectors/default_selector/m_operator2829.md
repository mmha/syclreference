---
layout: method
title: operator()
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  int operator()(const cl::sycl::device &) const:
    arguments:
      - description: " The device that is to be scored."
        name: device
        type: const cl::sycl::device &
    description: Overload that scores both CPUs and GPUs positive if they have SPIR support, GPUs are scored higher, scores host mode devices as positive but lower than a non-host device. This should never fail.
    return: " an integer representing the allocated score for the device."
    signature_with_names: int operator()(const cl::sycl::device & device) const
---
