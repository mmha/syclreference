---
layout: method
title: buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const T *, const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: const T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with host pointer
    return: ""
    signature_with_names: buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const T * hostPointer, const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const T *, const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: const T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with host pointer
    return: ""
    signature_with_names: buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const T * hostPointer, const range<dimensions> & r, const cl::sycl::property_list & propList)
  buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const shared_ptr_class<const T> &, const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Shared pointer to host data"
        name: hostPointer
        type: const shared_ptr_class<const T> &
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer.
    return: ""
    signature_with_names: buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const shared_ptr_class<const T> & hostPointer, const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const shared_ptr_class<const T> &, const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Shared pointer to host data"
        name: hostPointer
        type: const shared_ptr_class<const T> &
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer.
    return: ""
    signature_with_names: buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(const shared_ptr_class<const T> & hostPointer, const range<dimensions> & r, const cl::sycl::property_list & propList)
  explicit buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(cl::sycl::dmem_shptr):
    arguments:
      - description: ""
        name: impl
        type: cl::sycl::dmem_shptr
    description: ""
    return: ""
    signature_with_names: explicit buffer<const type-parameter-0-0, dimensions, type-parameter-0-2>(cl::sycl::dmem_shptr impl)
---
