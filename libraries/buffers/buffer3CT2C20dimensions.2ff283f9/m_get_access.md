---
layout: method
title: get_access
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler &)":
    arguments:
      - description: " Reference to the command group scope where the accessor is"
        name: cgh
        type: cl::sycl::handler &
    description: this function returns an accessor to the buffer in the given command_group scope.
    return: " Device accessor"
    signature_with_names: "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler & cgh)"
  "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler &, id<dimensions>, range<dimensions>)":
    annotation:
      - deprecated (Deprecated since SYCL 1.2.1)
    arguments:
      - description: " Reference to the command group scope where the accessor is"
        name: cgh
        type: cl::sycl::handler &
      - description: " the offset that the accessor will be able to update from."
        name: offset
        type: id<dimensions>
      - description: " the range in which the accessor will be updating the data."
        name: range
        type: range<dimensions>
    description: Returns an accessor to the buffer in the given command_group scope.
    return: " Device accessor"
    signature_with_names: "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler & cgh, id<dimensions> offset, range<dimensions> range)"
  "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler &, range<dimensions>, id<dimensions>)":
    arguments:
      - description: " Reference to the command group scope where the accessor is"
        name: cgh
        type: cl::sycl::handler &
      - description: " The range in which the accessor will be updating the data"
        name: range
        type: range<dimensions>
      - description: " The offset that the accessor will be able to update from"
        name: offset
        type: id<dimensions>
    description: Returns an accessor to the buffer in the given command group scope.
    return: " Device accessor"
    signature_with_names: "template <access::mode accessMode, access::target accessTarget>\naccessor<T, dimensions, accessMode, accessTarget> get_access(cl::sycl::handler & cgh, range<dimensions> range, id<dimensions> offset)"
  "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access()":
    description: Returns an accessor to the buffer, only used on the host side
    return: " Host accessor"
    signature_with_names: "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access()"
  "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access(id<dimensions>, range<dimensions>)":
    annotation:
      - deprecated (Deprecated since SYCL 1.2.1)
    arguments:
      - description: " The offset that the accessor will be able to update from."
        name: offset
        type: id<dimensions>
      - description: " The range in which the accessor will be updating the data."
        name: range
        type: range<dimensions>
    description: Returns an accessor to the buffer, only used on the host side
    return: " Host accessor"
    signature_with_names: "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access(id<dimensions> offset, range<dimensions> range)"
  "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access(range<dimensions>, id<dimensions>)":
    arguments:
      - description: " The range in which the accessor will be updating the data"
        name: range
        type: range<dimensions>
      - description: " The offset that the accessor will be able to update from"
        name: offset
        type: id<dimensions>
    description: Returns an accessor to the buffer, only used on the host side
    return: " Host accessor"
    signature_with_names: "template <access::mode accessMode>\naccessor<T, dimensions, accessMode, access::target::host_buffer> get_access(range<dimensions> range, id<dimensions> offset)"
---
