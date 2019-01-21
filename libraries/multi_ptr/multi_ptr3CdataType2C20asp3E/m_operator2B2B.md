---
layout: method
title: operator++
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  multi_ptr<dataT, addressSpace> & operator++():
    description: Increments the underlying pointer by 1
    return: " This object"
    signature_with_names: multi_ptr<dataT, addressSpace> & operator++()
  multi_ptr<dataT, addressSpace> operator++(int):
    arguments:
      - description: ""
        name: unnamed-0
        type: int
        unnamed: true
    description: Increments the underlying pointer by 1 and returns a new multi_ptr with the value of the previous pointer
    return: " New multi_ptr object with the old pointer value"
    signature_with_names: multi_ptr<dataT, addressSpace> operator++(int)
---
