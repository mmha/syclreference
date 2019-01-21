---
layout: method
title: buffer<T, dimensions, AllocatorT>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  buffer<T, dimensions, AllocatorT>(T *, const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage in case the"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer. In this case there is a host pointer, potentially initialized, but the user has not given the runtime any ownership, therefore the deleter has to be null. A Copy in is performed if the pointer is not null. If it is null, the data is initialized (new) inside the runtime. A copy out to hostPointer is performed by default.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(T * hostPointer, const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(T *, const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer. In this case there is a host pointer, potentially initialized, but the user has not given the runtime any ownership, therefore the deleter has to be null. A Copy in is performed if the pointer is not null. If it is null, the data is initialized (new) inside the runtime. A copy out to hostPointer is performed by default.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(T * hostPointer, const range<dimensions> & r, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(buffer<T, dimensions> &, const id<dimensions> &, const range<dimensions> &):
    arguments:
      - description: " Existing buffer that will act as the parent"
        name: b
        type: buffer<T, dimensions> &
      - description: " Offset of the original data to where the sub-buffer data"
        name: base_index
        type: const id<dimensions> &
      - description: " Range of the original data that will be used in the"
        name: sub_range
        type: const range<dimensions> &
    description: Construct a buffer as a subset from an existing buffer.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(buffer<T, dimensions> & b, const id<dimensions> & base_index, const range<dimensions> & sub_range)
  buffer<T, dimensions, AllocatorT>(cl_mem, cl::sycl::queue &, cl::sycl::event):
    annotation:
      - deprecated (This constructor is deprecated in SYCL 1.2.1, Please use the OpenCL interop constructor that accepts a SYCL context instead.)
    arguments:
      - description: " the user-provided OpenCL object that will be used by the"
        name: mem_object
        type: cl_mem
      - description: " the queue holding the context associated with the mem_object"
        name: fromQueue
        type: cl::sycl::queue &
      - description: " if provided signals that the cl_mem object has been"
        name: available_event
        type: cl::sycl::event
    description: Construct a buffer from an OpenCL object.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(cl_mem mem_object, cl::sycl::queue & fromQueue, cl::sycl::event available_event)
  buffer<T, dimensions, AllocatorT>(cl_mem, const cl::sycl::context &, cl::sycl::event):
    arguments:
      - description: " the user-provided OpenCL object that will be used by the"
        name: mem_object
        type: cl_mem
      - description: " the context associated with the mem_object object"
        name: syclContext
        type: const cl::sycl::context &
      - description: " if provided signals that the cl_mem object has been"
        name: available_event
        type: cl::sycl::event
    description: Construct a buffer from an OpenCL object.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(cl_mem mem_object, const cl::sycl::context & syclContext, cl::sycl::event available_event)
  buffer<T, dimensions, AllocatorT>(const T *, const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: const T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with host pointer. The user has given a const pointer, but the buffer is not const, so the runtime copies the data into a temporary space created using the given allocator. If the given allocator is a null allocator, this fails.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const T * hostPointer, const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(const T *, const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Pointer to host data"
        name: hostPointer
        type: const T *
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with host pointer. The user has given a const pointer, but the buffer is not const, so the runtime copies the data into a temporary space created using the given allocator. If the given allocator is a null allocator, this fails.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const T * hostPointer, const range<dimensions> & r, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage in case the"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer without a host pointer. The runtime will only use internally allocated memory and no copy in or out is defined. The given allocator is used to create internal storage in case the runtime requires it.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer without a host pointer. The runtime will only use internally allocated memory and no copy in or out is defined. The given allocator is used to create internal storage in case the runtime requires it.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const range<dimensions> & r, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(const shared_ptr_class<T> &, const range<dimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Shared pointer to host data"
        name: hostPointer
        type: const shared_ptr_class<T> &
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer. The user has given a shared pointer, therefore the data is explicitly shared between the user and the runtime. If the hostPointer is null, no data is copied in, and data is initialized inside the runtime. Data is copied out if the reference count of the runtime is less than the reference count of the shared pointer.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const shared_ptr_class<T> & hostPointer, const range<dimensions> & r, AllocatorT allocator, const cl::sycl::property_list & propList)
  buffer<T, dimensions, AllocatorT>(const shared_ptr_class<T> &, const range<dimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Shared pointer to host data"
        name: hostPointer
        type: const shared_ptr_class<T> &
      - description: " Range of the buffer"
        name: r
        type: const range<dimensions> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer with a host pointer. The user has given a shared pointer, therefore the data is explicitly shared between the user and the runtime. If the hostPointer is null, no data is copied in, and data is initialized inside the runtime. Data is copied out if the reference count of the runtime is less than the reference count of the shared pointer.
    return: ""
    signature_with_names: buffer<T, dimensions, AllocatorT>(const shared_ptr_class<T> & hostPointer, const range<dimensions> & r, const cl::sycl::property_list & propList)
  explicit buffer<T, dimensions, AllocatorT>(cl::sycl::dmem_shptr):
    arguments:
      - description: ""
        name: impl
        type: cl::sycl::dmem_shptr
    description: Creates a new public buffer object given an internal memory object. Implementation only
    return: ""
    signature_with_names: explicit buffer<T, dimensions, AllocatorT>(cl::sycl::dmem_shptr impl)
  explicit buffer<T, dimensions, AllocatorT>(vector_class<T> &, const cl::sycl::property_list &):
    arguments:
      - description: " Vector to construct the buffer from"
        name: v
        type: vector_class<T> &
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer from an std::vector, this is non-standard. A shared pointer is created from the raw data of the pointer, and a null-deleter is used to avoid the runtime clearing up the user-pointer. The range of the buffer is extracted from the size of the vector. The allocator from the vector is used as an allocator for the buffer.
    return: ""
    signature_with_names: explicit buffer<T, dimensions, AllocatorT>(vector_class<T> & v, const cl::sycl::property_list & propList)
  "template <typename Iterator>\nbuffer<T, dimensions, AllocatorT>(Iterator, Iterator, AllocatorT, const cl::sycl::property_list &)":
    arguments:
      - description: " Iterator starting the range"
        name: begin
        type: Iterator
      - description: "  Iterator ending the range"
        name: end
        type: Iterator
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer initialized by the given iterator range. This range is read-only, is not written.
    return: ""
    signature_with_names: "template <typename Iterator>\nbuffer<T, dimensions, AllocatorT>(Iterator begin, Iterator end, AllocatorT allocator, const cl::sycl::property_list & propList)"
  "template <typename Iterator>\nbuffer<T, dimensions, AllocatorT>(Iterator, Iterator, const cl::sycl::property_list &)":
    arguments:
      - description: " Iterator starting the range"
        name: begin
        type: Iterator
      - description: "  Iterator ending the range"
        name: end
        type: Iterator
      - description: " List of buffer properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Constructs a buffer initialized by the given iterator range. This range is read-only, is not written.
    return: ""
    signature_with_names: "template <typename Iterator>\nbuffer<T, dimensions, AllocatorT>(Iterator begin, Iterator end, const cl::sycl::property_list & propList)"
---
