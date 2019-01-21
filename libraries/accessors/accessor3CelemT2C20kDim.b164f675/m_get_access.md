---
layout: method
title: get_access
owner: __MISSING__
brief: Obtains a normal accessor from the placeholder accessor
tags:
  - method
defined-in-file: ""
overloads:
  accessor<elemT, kDims, kMode, kTarget, access::placeholder::false_t> get_access(cl::sycl::handler &) const:
    arguments:
      - description: " Command group handler where the accessor will be used"
        name: commandHandler
        type: cl::sycl::handler &
    description: Obtains a normal accessor from the placeholder accessor
    return: " Normal accessor that does not need to be registered"
    signature_with_names: accessor<elemT, kDims, kMode, kTarget, access::placeholder::false_t> get_access(cl::sycl::handler & commandHandler) const
---
