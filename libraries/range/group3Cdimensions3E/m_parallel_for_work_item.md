---
layout: method
title: parallel_for_work_item
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename workItemFunctionT>\nvoid parallel_for_work_item(const workItemFunctionT &) const":
    arguments:
      - description: " The functor to execute"
        name: func
        type: const workItemFunctionT &
    description: Inner loop of parallel_for_work_group
    return: ""
    signature_with_names: "template <typename workItemFunctionT>\nvoid parallel_for_work_item(const workItemFunctionT & func) const"
  "template <typename workItemFunctionT>\nvoid parallel_for_work_item(range<dimensions>, const workItemFunctionT &) const":
    arguments:
      - description: " The logical local range"
        name: flexibleRange
        type: range<dimensions>
      - description: " The functor to execute"
        name: func
        type: const workItemFunctionT &
    description: Inner loop of parallel_for_work_group
    return: ""
    signature_with_names: "template <typename workItemFunctionT>\nvoid parallel_for_work_item(range<dimensions> flexibleRange, const workItemFunctionT & func) const"
---
