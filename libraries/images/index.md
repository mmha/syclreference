---
layout: library
title: "Images"
owner: __MISSING__
brief: __MISSING__
tags:
  - library
library-type: sourcefile
typedefs:
  byte_t:
    definition: unsigned char
    description: ""
  context_bound:
    definition: buffer::context_bound
    description: The context_bound property adds the requirement that the SYCL image can only be associated with a single SYCL context that is provided to the property.
  use_host_ptr:
    definition: buffer::use_host_ptr
    description: The use_host_ptr property adds the requirement that the SYCL runtime must not allocate any memory for the image and instead uses the provided host pointer directly.
  use_mutex:
    definition: buffer::use_mutex
    description: The use_mutex property adds the requirement that the memory which is owned by the SYCL image can be shared with the application via a mutex_class provided to the property. The mutex is locked by the runtime whenever the data is in use and unlocked otherwise. Data is synchronized with host data when the mutex is unlocked by the runtime.
---
