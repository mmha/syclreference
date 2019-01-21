---
layout: method
title: wait
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  static void wait(const vector_class<cl::sycl::event> &):
    arguments:
      - description: " List of events to wait"
        name: eventList
        type: const vector_class<cl::sycl::event> &
    description: Waits for all the events in the list
    return: ""
    signature_with_names: static void wait(const vector_class<cl::sycl::event> & eventList)
  void wait():
    description: Waits for the event to complete.
    return: ""
    signature_with_names: void wait()
---
