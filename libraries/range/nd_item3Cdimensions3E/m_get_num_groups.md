---
layout: method
title: get_num_groups
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  range<dimensions> get_num_groups() const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_num_groups with nd_item::get_group_range.)
    description: Returns the group range of the enqueued nd_range.
    return: " the value of the group range for all dimensions."
    signature_with_names: range<dimensions> get_num_groups() const
  size_t get_num_groups(int) const:
    annotation:
      - deprecated (SYCL 1.2.1 revision 3 replaces nd_item::get_num_groups with nd_item::get_group_range.)
    arguments:
      - description: " of the range to be returned. Must be in the range [0,2]"
        name: dimension
        type: int
    description: Returns the group range of the enqueued nd_range for a specific dimension.
    return: " the value of the group range for all dimensions."
    signature_with_names: size_t get_num_groups(int dimension) const
---
