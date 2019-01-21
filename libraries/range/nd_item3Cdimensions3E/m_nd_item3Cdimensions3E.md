---
layout: method
title: nd_item<dimensions>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  nd_item<dimensions>(const detail::nd_item_base &):
    arguments:
      - description: ""
        name: i
        type: const detail::nd_item_base &
    description: converts the derived nd_item<dimensions> class to its base class Its as for APIs that use id structs.
    return: ""
    signature_with_names: nd_item<dimensions>(const detail::nd_item_base & i)
  nd_item<dimensions>(const nd_item<dimensions> &):
    annotation:
      - default
    arguments:
      - description: ""
        name: rhs
        type: const nd_item<dimensions> &
    description: copy constructor is public
    return: ""
    signature_with_names: nd_item<dimensions>(const nd_item<dimensions> & rhs)
---
