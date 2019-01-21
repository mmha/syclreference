---
layout: class
title: accessor<elemT, kDims, kMode, kTarget, isPlaceholder>
owner: __MISSING__
brief: Public facing interface class for allowing users access to buffer objects, image objects and local memory from within kernel functions and the host. The accessor class has many different constructors and operators available depending on the class template arguments including access target, access mode and dimensions. These constructors and operators are implemented using an enable_if technique in order to avoid a large amount of inheritance and code duplication. In order to reduce the complexity the enable_if conditions are predefined using static const const booleans and the enable_if definitions themselves are defined using the COMPUTECPP_ENABLE_IF macro. The accessor class also has the COMPUTECPP_CONVERT_ATTR macro attached to the end of the struct declaration, this is used during the compilers parameter flattening mechanism. The accessor class also has the COMPUTECPP_ACCESSOR_WINDOWS_ALIGNMENT and COMPUTECPP_ACCESSOR_LINUX_ALIGNMENT macros which align the accessor class to the pointer size, the reason for this is that for environments where the host and device pointer sizes don't match the kernel argument offsets can sometimes misalign, aligning the accessor resolves this.
tags:
  - class
defined-in-file: ""
declaration: "template <typename elemT, int kDims, access::mode kMode, access::target kTarget, access::placeholder isPlaceholder>\nclass cl::sycl::accessor;"
dtor: unspecified
fields:
  is_atomic_ctr:
    description: ""
    type: const bool
  is_const_buffer_ctr:
    description: ""
    type: const bool
  is_global_buffer_ctr:
    description: Predefined static const declarations of the const boolean expression used as enable_if conditions.
    type: const bool
  is_global_or_const_atom_ctr:
    description: ""
    type: const bool
  is_host_buffer_ctr:
    description: ""
    type: const bool
  is_host_image_ctr:
    description: ""
    type: const bool
  is_image_array_ctr:
    description: ""
    type: const bool
  is_image_ctr:
    description: ""
    type: const bool
  is_local_ctr:
    description: ""
    type: const bool
  is_n_dim:
    description: ""
    type: const bool
  is_non_local_ctr:
    description: ""
    type: const bool
namespace:
  - cl
  - sycl
---
