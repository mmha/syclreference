---
layout: method
title: create_sub_devices
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(const vector_class<size_t> &) const":
    arguments:
      - description: " A vector of sizes for the resulting sub devices."
        name: counts
        type: const vector_class<size_t> &
    description: Partition device into sub devices by explicitly stating the number of compute units used by each device.
    return: " Vector of sub devices. The number of sub devices created is the"
    signature_with_names: "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(const vector_class<size_t> & counts) const"
  "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(info::partition_affinity_domain) const":
    arguments:
      - description: " Affinity domain used for the partitioning."
        name: affinityDomain
        type: info::partition_affinity_domain
    description: Partition device into sub devices using the provided affinity domain.
    return: " Vector of sub devices."
    signature_with_names: "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(info::partition_affinity_domain affinityDomain) const"
  "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(size_t) const":
    arguments:
      - description: " Desired number of sub devices."
        name: nbSubDev
        type: size_t
    description: Partition device into sub devices evenly.
    return: " Vector of sub devices."
    signature_with_names: "template <info::partition_property prop>\nvector_class<cl::sycl::device> create_sub_devices(size_t nbSubDev) const"
---
