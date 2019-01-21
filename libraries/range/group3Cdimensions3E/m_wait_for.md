---
layout: method
title: wait_for
owner: __MISSING__
brief: Waits on each given device_event
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename... eventTN>\nvoid wait_for(eventTN...) const":
    arguments:
      - description: " Pack of device_events"
        name: events
        type: eventTN...
    description: Waits on each given device_event
    return: ""
    signature_with_names: "template <typename... eventTN>\nvoid wait_for(eventTN... events) const"
---
