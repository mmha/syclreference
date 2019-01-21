---
layout: method
title: get_info
owner: __MISSING__
brief: Retrieves information about the program. The runtime query the OpenCL API and then converts the result into the SYCL representation before returning it.
tags:
  - method
defined-in-file: ""
overloads:
  "template <info::program param>\ntypename info::param_traits<info::program, param>::return_type get_info() const":
    description: Retrieves information about the program. The runtime query the OpenCL API and then converts the result into the SYCL representation before returning it.
    return: " The information in the SYCL format."
    signature_with_names: "template <info::program param>\ntypename info::param_traits<info::program, param>::return_type get_info() const"
---
