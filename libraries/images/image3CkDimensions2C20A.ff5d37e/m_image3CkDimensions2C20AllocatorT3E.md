---
layout: method
title: image<kDimensions, AllocatorT>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
is_ctor: true
overloads:
  image<kDimensions, AllocatorT>(cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with no host pointer, performing device side allocation of the buffer, this means that on destruction the data will not be copied back unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, AllocatorT allocator, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with no host pointer, performing device side allocation of the buffer, this means that on destruction the data will not be copied back unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(cl_mem, const cl::sycl::context &, cl::sycl::event):
    arguments:
      - description: ""
        name: memObject
        type: cl_mem
      - description: ""
        name: syclContext
        type: const cl::sycl::context &
      - description: ""
        name: availableEvent
        type: cl::sycl::event
    description: ""
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(cl_mem memObject, const cl::sycl::context & syclContext, cl::sycl::event availableEvent)
  image<kDimensions, AllocatorT>(const image<kDimensions, AllocatorT> &):
    annotation:
      - default
    arguments:
      - description: ""
        name: unnamed-0
        type: const image<kDimensions, AllocatorT> &
        unnamed: true
    description: Copy constructor. Copy the image descriptor of the original image. After the copy, both image object will point to the same underlying memory.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(const image<kDimensions, AllocatorT> &)
  image<kDimensions, AllocatorT>(const void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: const void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a raw host pointer to the image data. On object destruction, the data will not be copied back unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(const void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, AllocatorT allocator, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(const void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: const void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a constant raw host pointer to the image data. On object destruction, the data will not be copied back, unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(const void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(image<kDimensions, AllocatorT> &&):
    arguments:
      - description: ""
        name: rhs
        type: image<kDimensions, AllocatorT> &&
    description: Move Constructor. Moves the image descriptor of the original image. After the move, rhs will be invalid.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(image<kDimensions, AllocatorT> && rhs)
  image<kDimensions, AllocatorT>(shared_ptr_class<void>, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " shared pointer to the image data."
        name: sharedPtr
        type: shared_ptr_class<void>
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a shared host pointer to the image data.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(shared_ptr_class<void> sharedPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, AllocatorT allocator, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(shared_ptr_class<void>, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " shared pointer to the image data."
        name: sharedPtr
        type: shared_ptr_class<void>
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a shared host pointer to the image data.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(shared_ptr_class<void> sharedPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, AllocatorT, const cl::sycl::property_list &):
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a raw host pointer to the image data. On object destruction, the data will be copied to the specified host pointer unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, AllocatorT allocator, const cl::sycl::property_list & propList)
  image<kDimensions, AllocatorT>(void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::property_list &):
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with a raw host pointer to the image data. On object destruction, the data will be copied to the specified host pointer unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: image<kDimensions, AllocatorT>(void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::property_list & propList)
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, AllocatorT, const cl::sycl::property_list &)":
    arguments:
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with no host pointer, performing device side allocation of the buffer, this means that on destruction the data will not be copied back unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, AllocatorT allocator, const cl::sycl::property_list & propList)"
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, const cl::sycl::property_list &)":
    arguments:
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type and range, with no host pointer, performing device side allocation of the buffer, this means that on destruction the data will not be copied back unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, const cl::sycl::property_list & propList)"
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(shared_ptr_class<void>, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, AllocatorT, const cl::sycl::property_list &)":
    arguments:
      - description: " Shared pointer to the image data."
        name: sharedPtr
        type: shared_ptr_class<void>
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type, range and pitch, with a shared host pointer to the image data.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(shared_ptr_class<void> sharedPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, AllocatorT allocator, const cl::sycl::property_list & propList)"
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(shared_ptr_class<void>, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, const cl::sycl::property_list &)":
    arguments:
      - description: " Shared pointer to the image data."
        name: sharedPtr
        type: shared_ptr_class<void>
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type, range and pitch, with a shared host pointer to the image data.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(shared_ptr_class<void> sharedPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, const cl::sycl::property_list & propList)"
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, AllocatorT, const cl::sycl::property_list &)":
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " The allocator used to create internal storage"
        name: allocator
        type: AllocatorT
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type, range and pitch, with a raw host pointer to the image data. On object destruction, the data will be copied to the specified host pointer unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, AllocatorT allocator, const cl::sycl::property_list & propList)"
  "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(void *, cl::sycl::image_channel_order, cl::sycl::image_channel_type, const range<kDimensions> &, const cl::sycl::image::pitch_range_t &, const cl::sycl::property_list &)":
    arguments:
      - description: " Raw pointer to the image data."
        name: hostPtr
        type: void *
      - description: " Image channel order."
        name: order
        type: cl::sycl::image_channel_order
      - description: " Image channel type."
        name: type
        type: cl::sycl::image_channel_type
      - description: " Image range."
        name: rng
        type: const range<kDimensions> &
      - description: " Image pitch."
        name: pit
        type: const cl::sycl::image::pitch_range_t &
      - description: " List of image properties"
        name: propList
        type: const cl::sycl::property_list &
    description: Construct an image of the specified channel_order and channel_type, range and pitch, with a raw host pointer to the image data. On object destruction, the data will be copied to the specified host pointer unless a final pointer is specified using set_final_data() in which case that specified pointer will be used.
    return: ""
    signature_with_names: "template <typename overloadDependantT, typename >\nimage<kDimensions, AllocatorT>(void * hostPtr, cl::sycl::image_channel_order order, cl::sycl::image_channel_type type, const range<kDimensions> & rng, const cl::sycl::image::pitch_range_t & pit, const cl::sycl::property_list & propList)"
---
