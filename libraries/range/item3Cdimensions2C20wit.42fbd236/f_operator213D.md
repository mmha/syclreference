---
layout: function
title: operator!=
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  bool operator!=(const h_item<dimensions> &, const h_item<dimensions> &):
    arguments:
      - description: ""
        name: lhs
        type: const h_item<dimensions> &
      - description: " Object to compare to"
        name: rhs
        type: const h_item<dimensions> &
    description: Non-equality operator
    return: " True if at least one member variable not the same"
    signature_with_names: bool operator!=(const h_item<dimensions> & lhs, const h_item<dimensions> & rhs)
  bool operator!=(const item<dimensions, with_offset> &, const item<dimensions, with_offset> &):
    arguments:
      - description: ""
        name: lhs
        type: const item<dimensions, with_offset> &
      - description: " Object to compare to"
        name: rhs
        type: const item<dimensions, with_offset> &
    description: Non-equality operator
    return: " True if at least one member variable not the same"
    signature_with_names: bool operator!=(const item<dimensions, with_offset> & lhs, const item<dimensions, with_offset> & rhs)
  bool operator!=(const nd_item<dimensions> &, const nd_item<dimensions> &):
    arguments:
      - description: ""
        name: lhs
        type: const nd_item<dimensions> &
      - description: " Object to compare to"
        name: rhs
        type: const nd_item<dimensions> &
    description: Non-equality operator
    return: " True if at least one member variable not the same"
    signature_with_names: bool operator!=(const nd_item<dimensions> & lhs, const nd_item<dimensions> & rhs)
---
