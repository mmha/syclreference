---
layout: method
title: queue
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  explicit queue(cl::sycl::dqueue_shptr):
    arguments:
      - description: ""
        name: impl
        type: cl::sycl::dqueue_shptr
    description: Creates a queue using a specific implementation object.
    return: ""
    signature_with_names: explicit queue(cl::sycl::dqueue_shptr impl)
  explicit queue(const cl::sycl::property_list &):
    arguments:
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a default device selector.
    return: ""
    signature_with_names: explicit queue(const cl::sycl::property_list & propList)
  queue(cl::sycl::queue &&):
    arguments:
      - description: ""
        name: rhs
        type: cl::sycl::queue &&
    description: Completely moves the contents of a queue to that of another queue.
    return: ""
    signature_with_names: queue(cl::sycl::queue && rhs)
  queue(cl_command_queue, const cl::sycl::context &, const cl::sycl::async_handler &):
    arguments:
      - description: ""
        name: clqueue
        type: cl_command_queue
      - description: " a valid OpenCL context"
        name: s_context
        type: const cl::sycl::context &
      - description: " User defined "
        name: asyncHandler
        type: const cl::sycl::async_handler &
    description: Construct a queue object from a given OpenCL object
    return: ""
    signature_with_names: queue(cl_command_queue clqueue, const cl::sycl::context & s_context, const cl::sycl::async_handler & asyncHandler)
  queue(const cl::sycl::async_handler &, const cl::sycl::property_list &):
    arguments:
      - description: " User defined "
        name: asyncHandler
        type: const cl::sycl::async_handler &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a default device selector.
    return: ""
    signature_with_names: queue(const cl::sycl::async_handler & asyncHandler, const cl::sycl::property_list & propList)
  queue(const cl::sycl::context &, const cl::sycl::device_selector &, const cl::sycl::async_handler &, const cl::sycl::property_list &):
    arguments:
      - description: " Context in which the queue will be created."
        name: syclContext
        type: const cl::sycl::context &
      - description: " Used to get a device from the context"
        name: selector
        type: const cl::sycl::device_selector &
      - description: ""
        name: asyncHandler
        type: const cl::sycl::async_handler &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a user defined device selector against a specific context. The device selector to get the device to construct the queue.
    return: ""
    signature_with_names: queue(const cl::sycl::context & syclContext, const cl::sycl::device_selector & selector, const cl::sycl::async_handler & asyncHandler, const cl::sycl::property_list & propList)
  queue(const cl::sycl::context &, const cl::sycl::device_selector &, const cl::sycl::property_list &):
    arguments:
      - description: " Context in which the queue will be created."
        name: syclContext
        type: const cl::sycl::context &
      - description: " Used to get a device from the context"
        name: selector
        type: const cl::sycl::device_selector &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a user defined device selector against a specific context. The device selector to get the device to construct the queue.
    return: ""
    signature_with_names: queue(const cl::sycl::context & syclContext, const cl::sycl::device_selector & selector, const cl::sycl::property_list & propList)
  queue(const cl::sycl::device &, const cl::sycl::async_handler &, const cl::sycl::property_list &):
    arguments:
      - description: " The device to use to create the queue"
        name: dev
        type: const cl::sycl::device &
      - description: " User defined "
        name: asyncHandler
        type: const cl::sycl::async_handler &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct a queue from a given device, creating an implicit context in the process.
    return: ""
    signature_with_names: queue(const cl::sycl::device & dev, const cl::sycl::async_handler & asyncHandler, const cl::sycl::property_list & propList)
  queue(const cl::sycl::device &, const cl::sycl::property_list &):
    arguments:
      - description: " The device to use to create the queue"
        name: dev
        type: const cl::sycl::device &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct a queue from a given device, creating an implicit context in the process.
    return: ""
    signature_with_names: queue(const cl::sycl::device & dev, const cl::sycl::property_list & propList)
  queue(const cl::sycl::device_selector &, const cl::sycl::async_handler &, const cl::sycl::property_list &):
    arguments:
      - description: " User defined "
        name: deviceSelector
        type: const cl::sycl::device_selector &
      - description: " User defined "
        name: asyncHandler
        type: const cl::sycl::async_handler &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a user defined device selector. The device selector constructor to get the device to construct the queue.
    return: ""
    signature_with_names: queue(const cl::sycl::device_selector & deviceSelector, const cl::sycl::async_handler & asyncHandler, const cl::sycl::property_list & propList)
  queue(const cl::sycl::device_selector &, const cl::sycl::property_list &):
    arguments:
      - description: " User defined "
        name: deviceSelector
        type: const cl::sycl::device_selector &
      - description: " List of queue properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a queue using a user defined device selector. The device selector constructor to get the device to construct the queue.
    return: ""
    signature_with_names: queue(const cl::sycl::device_selector & deviceSelector, const cl::sycl::property_list & propList)
  queue(const cl::sycl::queue &):
    arguments:
      - description: " a queue to be copied over to the returned object"
        name: rhs
        type: const cl::sycl::queue &
    description: Construct a queue object by copying the contents of a given queue object.
    return: ""
    signature_with_names: queue(const cl::sycl::queue & rhs)
---
