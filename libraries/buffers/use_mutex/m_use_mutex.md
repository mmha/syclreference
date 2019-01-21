---
layout: method
title: use_mutex
owner: __MISSING__
brief: Constructs a SYCL use_mutex property instance with a reference to mutexRef parameter provided.
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  use_mutex(cl::sycl::mutex_class &):
    arguments:
      - description: " Mutex to be associated with the property and the buffer."
        name: mutexRef
        type: cl::sycl::mutex_class &
    description: Constructs a SYCL use_mutex property instance with a reference to mutexRef parameter provided.
    return: ""
    signature_with_names: use_mutex(cl::sycl::mutex_class & mutexRef)
---
