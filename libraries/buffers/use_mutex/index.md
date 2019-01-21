---
layout: class
title: use_mutex
owner: __MISSING__
brief: The use_mutex property adds the requirement that the memory which is owned by the SYCL buffer can be shared with the application via a mutex_class provided to the property. The mutex is locked by the runtime whenever the data is in use and unlocked otherwise. Data is synchronized with host data when the mutex is unlocked by the runtime.
tags:
  - class
defined-in-file: ""
declaration: "\nclass cl::sycl::property::buffer::use_mutex;"
dtor: unspecified
namespace:
  - cl
  - sycl
  - property
  - buffer
---
