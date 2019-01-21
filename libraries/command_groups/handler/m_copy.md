---
layout: method
title: copy
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined-in-file: ""
overloads:
  "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>, THostPtr *)":
    arguments:
      - description: " Accessor that is used to access the buffer or image"
        name: acc
        type: accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>
      - description: " Host pointer that will be updated"
        name: hostPtr
        type: THostPtr *
    description: Copies the data from the device accessor to the host pointer. hostPtr must have enough space allocated to match the size of the accessor data.
    return: ""
    signature_with_names: "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder> acc, THostPtr * hostPtr)"
  "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>, shared_ptr_class<THostPtr>)":
    arguments:
      - description: " Accessor that is used to access the buffer or image"
        name: acc
        type: accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>
      - description: " Host pointer that will be updated"
        name: hostPtr
        type: shared_ptr_class<THostPtr>
    description: Copies the data from the device accessor to the host pointer. hostPtr must have enough space allocated to match the size of the accessor data.
    return: ""
    signature_with_names: "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder> acc, shared_ptr_class<THostPtr> hostPtr)"
  "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(const THostPtr *, accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>)":
    arguments:
      - description: " Host pointer that points to the new data"
        name: hostPtr
        type: const THostPtr *
      - description: " Accessor that is used to access the buffer or image"
        name: acc
        type: accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>
    description: Copies the data from the host pointer to the device accessor. hostPtr must have enough space allocated to match the size of the accessor data.
    return: ""
    signature_with_names: "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(const THostPtr * hostPtr, accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder> acc)"
  "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(shared_ptr_class<THostPtr>, accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>)":
    arguments:
      - description: " Host pointer that points to the new data"
        name: hostPtr
        type: shared_ptr_class<THostPtr>
      - description: " Accessor that is used to access the buffer or image"
        name: acc
        type: accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder>
    description: Copies the data from the host pointer to the device accessor. hostPtr must have enough space allocated to match the size of the accessor data.
    return: ""
    signature_with_names: "template <typename TAcc, typename THostPtr, int dims, cl::sycl::access::mode accessMode, cl::sycl::access::target accessTarget, access::placeholder isPlaceholder, typename overloadDependantT, typename >\nvoid copy(shared_ptr_class<THostPtr> hostPtr, accessor<TAcc, dims, accessMode, accessTarget, isPlaceholder> acc)"
  "template <typename TOrig, typename TDest, int dims, cl::sycl::access::mode accessModeOrig, cl::sycl::access::mode accessModeDest, cl::sycl::access::target accessTargetOrig, cl::sycl::access::target accessTargetDest, access::placeholder isPlaceholderOrig, access::placeholder isPlaceholderDest, typename overloadDependantT, typename >\nvoid copy(accessor<TOrig, dims, accessModeOrig, accessTargetOrig, isPlaceholderOrig>, accessor<TDest, dims, accessModeDest, accessTargetDest, isPlaceholderDest>)":
    arguments:
      - description: " Accessor with the data that will be copied from"
        name: originAcc
        type: accessor<TOrig, dims, accessModeOrig, accessTargetOrig, isPlaceholderOrig>
      - description: " Accessor with the data that will be copied to"
        name: destinationAcc
        type: accessor<TDest, dims, accessModeDest, accessTargetDest, isPlaceholderDest>
    description: Copies data associated with the origin accessor to the data associated with the destination accessor.
    return: ""
    signature_with_names: "template <typename TOrig, typename TDest, int dims, cl::sycl::access::mode accessModeOrig, cl::sycl::access::mode accessModeDest, cl::sycl::access::target accessTargetOrig, cl::sycl::access::target accessTargetDest, access::placeholder isPlaceholderOrig, access::placeholder isPlaceholderDest, typename overloadDependantT, typename >\nvoid copy(accessor<TOrig, dims, accessModeOrig, accessTargetOrig, isPlaceholderOrig> originAcc, accessor<TDest, dims, accessModeDest, accessTargetDest, isPlaceholderDest> destinationAcc)"
---
