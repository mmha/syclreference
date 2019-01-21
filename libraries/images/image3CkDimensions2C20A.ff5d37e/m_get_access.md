---
layout: method
title: get_access
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename T, access::mode accessMode>\naccessor<T, kDimensions, accessMode, access::target::host_image> get_access()":
    description: Create an accessor to the image.
    return: ""
    signature_with_names: "template <typename T, access::mode accessMode>\naccessor<T, kDimensions, accessMode, access::target::host_image> get_access()"
  "template <typename T, access::mode accessMode>\naccessor<T, kDimensions, accessMode, access::target::image> get_access(cl::sycl::handler &)":
    arguments:
      - description: " The command group handler"
        name: cgh
        type: cl::sycl::handler &
    description: Create an accessor to the image for command group
    return: ""
    signature_with_names: "template <typename T, access::mode accessMode>\naccessor<T, kDimensions, accessMode, access::target::image> get_access(cl::sycl::handler & cgh)"
---
