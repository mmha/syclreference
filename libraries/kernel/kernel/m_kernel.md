---
layout: method
title: kernel
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit kernel(cl::sycl::dkernel_shptr):
    arguments:
      - description: ""
        name: detail
        type: cl::sycl::dkernel_shptr
    description: ""
    return: ""
    signature_with_names: explicit kernel(cl::sycl::dkernel_shptr detail)
  kernel(cl::sycl::kernel &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::kernel &&
    description: Move constructor. Create a copy of a kernel.
    return: ""
    signature_with_names: kernel(cl::sycl::kernel && rhs)
  kernel(cl_kernel):
    annotation:
      - deprecated (kernel(cl_kernel) was deprecated in SYCL 1.2.1)
    arguments:
      - description: " an OpenCL kernel created using the OpenCL API."
        name: clKernel
        type: cl_kernel
    description: Create a kernel object from cl_kernel object created by an OpenCL runtime.
    return: ""
    signature_with_names: kernel(cl_kernel clKernel)
  kernel(cl_kernel, const cl::sycl::context &):
    arguments:
      - description: " Kernel object created by an OpenCL runtime"
        name: clKernel
        type: cl_kernel
      - description: " Context associated with the OpenCL kernel object"
        name: syclContext
        type: const cl::sycl::context &
    description: Constructs a kernel object from an OpenCL cl_kernel object
    return: ""
    signature_with_names: kernel(cl_kernel clKernel, const cl::sycl::context & syclContext)
  kernel(const cl::sycl::kernel &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::kernel &
    description: Copy constructor. Create a copy of a kernel.
    return: ""
    signature_with_names: kernel(const cl::sycl::kernel & rhs)
---
