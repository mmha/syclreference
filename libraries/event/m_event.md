---
layout: method
title: event
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  event():
    description: Constructs a ready SYCL event.
    return: ""
    signature_with_names: event()
  event(cl::sycl::event &&):
    arguments:
      - description: " will have its contents moved. after the operation rhs will be"
        name: rhs
        type: cl::sycl::event &&
    description: Default move constructor.
    return: ""
    signature_with_names: event(cl::sycl::event && rhs)
  event(cl_event):
    annotation:
      - deprecated (event(cl_event) was deprecated in SYCL 1.2.1)
    arguments:
      - description: ""
        name: unnamed-0
        type: cl_event
        unnamed: true
    description: Creates a SYCL event from an OpenCL event
    return: ""
    signature_with_names: event(cl_event)
  event(cl_event, const cl::sycl::context &):
    arguments:
      - description: ""
        name: clEvent
        type: cl_event
      - description: ""
        name: syclContext
        type: const cl::sycl::context &
    description: Creates a SYCL event from an OpenCL event
    return: ""
    signature_with_names: event(cl_event clEvent, const cl::sycl::context & syclContext)
  event(const cl::sycl::devent_shptr &):
    arguments:
      - description: ""
        name: impl
        type: const cl::sycl::devent_shptr &
    description: Internal constructor to create events from internal implementation objects
    return: ""
    signature_with_names: event(const cl::sycl::devent_shptr & impl)
  event(const cl::sycl::event &):
    arguments:
      - description: ""
        name: rhs
        type: const cl::sycl::event &
    description: Default copy constructor.
    return: ""
    signature_with_names: event(const cl::sycl::event & rhs)
---
