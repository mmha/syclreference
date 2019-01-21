---
layout: method
title: wait_and_throw
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  static void wait_and_throw(const vector_class<cl::sycl::event> &):
    arguments:
      - description: " List of events to wait"
        name: eventList
        type: const vector_class<cl::sycl::event> &
    description: Waits for all the events in the list. Exceptions may be thrown.
    return: ""
    signature_with_names: static void wait_and_throw(const vector_class<cl::sycl::event> & eventList)
  void wait_and_throw():
    description: Waits for the event to complete. Throws any exception that can be associated with the execution of the event
    return: ""
    signature_with_names: void wait_and_throw()
---
