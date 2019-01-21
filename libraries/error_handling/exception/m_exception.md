---
layout: method
title: exception
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  exception(cl::sycl::exception &&):
    arguments:
      - description: ""
        name: unnamed-0
        type: cl::sycl::exception &&
        unnamed: true
    description: ""
    return: ""
    signature_with_names: exception(cl::sycl::exception &&)
  exception(const cl::sycl::exception &):
    arguments:
      - description: ""
        name: unnamed-0
        type: const cl::sycl::exception &
        unnamed: true
    description: ""
    return: ""
    signature_with_names: exception(const cl::sycl::exception &)
  explicit exception(detail::sycl_log &&, cl::sycl::dcontext_shptr):
    arguments:
      - description: " The sycl_log to be associated with the error."
        name: syclLog
        type: detail::sycl_log &&
      - description: " Shared pointer to a detail context if applies"
        name: context
        type: cl::sycl::dcontext_shptr
    description: Constructs a exception from a sycl_log.
    return: ""
    signature_with_names: explicit exception(detail::sycl_log && syclLog, cl::sycl::dcontext_shptr context)
---
