---
layout: function
title: stream_value
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const bool &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The bool value to be streamed."
        name: rhs
        type: const bool &
    description: Inline function that streams a bool value to a stream object.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const bool & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const char &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The const char "
        name: rhs
        type: const char &
    description: Inline function that streams a const char & value to a stream object.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const char & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const char *):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The const char * value to be streamed."
        name: rhs
        type: const char *
    description: Inline function that streams a const char * value to a stream object.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const char * rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const cl::sycl::half &):
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " The half value to be streamed"
        name: rhs
        type: const cl::sycl::half &
    description: Streams a half value to a stream object
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const cl::sycl::half & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const cl::sycl::precision_manipulator &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The precision_manipulator be applied to the stream object."
        name: rhs
        type: const cl::sycl::precision_manipulator &
    description: Inline function that streams a precision manipulator to a stream object, applying the precision value.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const cl::sycl::precision_manipulator & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const cl::sycl::stream_manipulator &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The stream_manipulator be applied to the stream object."
        name: rhs
        type: const cl::sycl::stream_manipulator &
    description: Inline function that streams a manipulator to a stream object, applying the appropriate action.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const cl::sycl::stream_manipulator & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const detail::width_manipulator &):
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " Width manipulator specifying the new width"
        name: rhs
        type: const detail::width_manipulator &
    description: Sets the width used for streaming data to the value specified by rhs
    return: " Original stream object"
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const detail::width_manipulator & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const double &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The double value to be streamed."
        name: rhs
        type: const double &
    description: Inline function that streams a double value to a stream object.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const double & rhs)
  const cl::sycl::stream & stream_value(const cl::sycl::stream &, const float &):
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The float value to be streamed."
        name: rhs
        type: const float &
    description: Inline function that streams a float value to a stream object.
    return: ""
    signature_with_names: const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const float & rhs)
  "template <class dataType, typename overloadDependantT, typename >\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, dataType)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " Integral value"
        name: rhs
        type: dataType
    description: Streams an integral type into a stream
    return: " Original stream object"
    signature_with_names: "template <class dataType, typename overloadDependantT, typename >\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, dataType rhs)"
  "template <int dimensions, bool with_offset>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, const item<dimensions, with_offset> &, char *)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " item object"
        name: rhs
        type: const item<dimensions, with_offset> &
      - description: ""
        name: typeStr
        type: char *
    description: Streams an item object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions, bool with_offset>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, const item<dimensions, with_offset> & rhs, char * typeStr)"
  "template <int dimensions>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, const id<dimensions> &, char *)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " id object"
        name: rhs
        type: const id<dimensions> &
      - description: " Optional type name"
        name: typeStr
        type: char *
    description: Streams an id object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, const id<dimensions> & rhs, char * typeStr)"
  "template <int dimensions>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, const range<dimensions> &, char *)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " range object"
        name: rhs
        type: const range<dimensions> &
      - description: " Optional type name"
        name: typeStr
        type: char *
    description: Streams a range object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, const range<dimensions> & rhs, char * typeStr)"
  "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream &, const group<dimensions> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " group object"
        name: rhs
        type: const group<dimensions> &
    description: Streams a group object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const group<dimensions> & rhs)"
  "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream &, const h_item<dimensions> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " h_item object"
        name: rhs
        type: const h_item<dimensions> &
    description: Streams an h_item object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const h_item<dimensions> & rhs)"
  "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream &, const nd_item<dimensions> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " nd_item object"
        name: rhs
        type: const nd_item<dimensions> &
    description: Streams an nd_item object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const nd_item<dimensions> & rhs)"
  "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream &, const nd_range<dimensions> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " nd_range object"
        name: rhs
        type: const nd_range<dimensions> &
    description: Streams an nd_range object into a stream object
    return: " Original stream object"
    signature_with_names: "template <int dimensions>\nstatic const cl::sycl::stream & stream_value(const cl::sycl::stream & os, const nd_range<dimensions> & rhs)"
  "template <typename dataType, cl::sycl::access::address_space asp>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, const multi_ptr<dataType, asp> &)":
    arguments:
      - description: " The stream object to be streamed to"
        name: os
        type: const cl::sycl::stream &
      - description: " multi_ptr object to display in the stream"
        name: rhs
        type: const multi_ptr<dataType, asp> &
    description: Streams a multi_ptr object into a stream
    return: " Original stream object"
    signature_with_names: "template <typename dataType, cl::sycl::access::address_space asp>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, const multi_ptr<dataType, asp> & rhs)"
  "template <typename pointerT>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream &, pointerT *)":
    arguments:
      - description: " The stream object to be streamed to."
        name: os
        type: const cl::sycl::stream &
      - description: " The pointer value to be streamed."
        name: rhs
        type: pointerT *
    description: Template function that streams a pointer value to a stream object.
    return: ""
    signature_with_names: "template <typename pointerT>\nconst cl::sycl::stream & stream_value(const cl::sycl::stream & os, pointerT * rhs)"
---
