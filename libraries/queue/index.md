---
layout: class
title: queue
owner: __MISSING__
brief: The cl::sycl::queue object is the SYCL abstraction of the OpenCL object cl_command_queue. It is responsible for constructing the OpenCL cl_command_queue object and all OpenCL API functions that involve enqueuing. It can be constructed using either a cl::sycl::device_selector, a cl::sycl::context or using default behaviour. As the cl::sycl::queue object can be constructed using different methods, it maintains the ownership over objects that it can potentially be responsible for constructing and destructing.
tags:
  - class
defined-in-file: ""
declaration: "\nclass cl::sycl::queue;"
namespace:
  - cl
  - sycl
---
