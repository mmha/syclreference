---
layout: method
title: sampler
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit sampler(cl_sampler):
    annotation:
      - deprecated (sampler(cl_sampler) deprecated in SYCL 1.2.1, please also provide a SYCL context)
    arguments:
      - description: " OpenCL cl_sampler object/"
        name: clSampler
        type: cl_sampler
    description: Inter-op constructor that creates a sampler from a cl_sampler object.
    return: ""
    signature_with_names: explicit sampler(cl_sampler clSampler)
  sampler(cl::sycl::coordinate_normalization_mode, cl::sycl::addressing_mode, cl::sycl::filtering_mode):
    arguments:
      - description: " Value specifying whether normalized coordinates are"
        name: normalizedCoords
        type: cl::sycl::coordinate_normalization_mode
      - description: " The sampler addressing mode."
        name: addressMode
        type: cl::sycl::addressing_mode
      - description: " The sampler filter mode."
        name: filterMode
        type: cl::sycl::filtering_mode
    description: Constructor that creates a sampler from the sampler addressing mode sampler filter mode and a boolean specifying whether normalized coordinates are enabled.
    return: ""
    signature_with_names: sampler(cl::sycl::coordinate_normalization_mode normalizedCoords, cl::sycl::addressing_mode addressMode, cl::sycl::filtering_mode filterMode)
  sampler(cl::sycl::sampler &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::sampler &&
    description: Default move constructor.
    return: ""
    signature_with_names: sampler(cl::sycl::sampler && rhs)
  sampler(cl_sampler, const cl::sycl::context &):
    arguments:
      - description: " OpenCL cl_sampler object"
        name: clSampler
        type: cl_sampler
      - description: " Context associated with the OpenCL sampler object"
        name: syclContext
        type: const cl::sycl::context &
    description: Inter-op constructor that creates a sampler from a cl_sampler object
    return: ""
    signature_with_names: sampler(cl_sampler clSampler, const cl::sycl::context & syclContext)
  sampler(const bool, const cl::sycl::addressing_mode, const cl::sycl::filtering_mode):
    annotation:
      - deprecated (sampler::sampler(bool, addressing_mode, filtering_mode) deprecated. Usesampler::sampler(coordinate_normalization_mode, addressing_mode,filtering_mode) instead.)
    arguments:
      - description: " Boolean specifying whether normalized coordinates are"
        name: normalizedCoords
        type: const bool
      - description: " The sampler addressing mode."
        name: addressMode
        type: const cl::sycl::addressing_mode
      - description: " The sampler filter mode."
        name: filterMode
        type: const cl::sycl::filtering_mode
    description: Constructor that creates a sampler from the sampler addressing mode sampler filter mode and a boolean specifying whether normalized coordinates are enabled.
    return: ""
    signature_with_names: sampler(const bool normalizedCoords, const cl::sycl::addressing_mode addressMode, const cl::sycl::filtering_mode filterMode)
  sampler(const cl::sycl::sampler &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::sampler &
    description: Default copy constructor.
    return: ""
    signature_with_names: sampler(const cl::sycl::sampler & rhs)
---
