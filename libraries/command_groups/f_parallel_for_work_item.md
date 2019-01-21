---
layout: function
title: parallel_for_work_item
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename functorT, int dimensions>\nvoid parallel_for_work_item(group<dimensions>, const functorT &)":
    annotation:
      - deprecated (free function parallel_for_work_item was deprecated in SYCL 1.2.1)
    arguments:
      - description: ""
        name: groupID
        type: group<dimensions>
      - description: ""
        name: functor
        type: const functorT &
    description: inner loop of parallel_for_work_group, the Hierarchical API.
    return: ""
    signature_with_names: "template <typename functorT, int dimensions>\nvoid parallel_for_work_item(group<dimensions> groupID, const functorT & functor)"
  "template <typename functorT, int dimensions>\nvoid parallel_for_work_item(group<dimensions>, range<dimensions>, const functorT &)":
    annotation:
      - deprecated (free function parallel_for_work_item was deprecated in SYCL 1.2.1)
    arguments:
      - description: ""
        name: groupID
        type: group<dimensions>
      - description: ""
        name: localRange
        type: range<dimensions>
      - description: ""
        name: functor
        type: const functorT &
    description: inner loop of parallel_for_work_group with a logical local range, the Hierarchical API.
    return: ""
    signature_with_names: "template <typename functorT, int dimensions>\nvoid parallel_for_work_item(group<dimensions> groupID, range<dimensions> localRange, const functorT & functor)"
---
