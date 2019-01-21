---
layout: method
title: item<dimensions, with_offset>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  item<dimensions, with_offset>(const detail::item_base &):
    arguments:
      - description: ""
        name: itemBase
        type: const detail::item_base &
    description: converts the derived index_array class to its base class Its used for APIs that use id structs.
    return: ""
    signature_with_names: item<dimensions, with_offset>(const detail::item_base & itemBase)
  item<dimensions, with_offset>(const item<dimensions, with_offset> &):
    annotation:
      - default
    arguments:
      - description: ""
        name: rhs
        type: const item<dimensions, with_offset> &
    description: Copy constructor. Create a copy of another
    return: ""
    signature_with_names: item<dimensions, with_offset>(const item<dimensions, with_offset> & rhs)
---
