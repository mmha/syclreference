---
layout: function
title: upsample
owner: __MISSING__
brief: Returns `result[i] = (hi[i] << 8) | lo[i]`
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename I1, typename I2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_geninteger8bit<I1>::value && detail::builtin::is_ugeninteger8bit<I2>::value, detail::builtin::is_geninteger16bit<I1>::value && detail::builtin::is_ugeninteger16bit<I2>::value, detail::builtin::is_geninteger32bit<I1>::value && detail::builtin::is_ugeninteger32bit<I2>::value>::value), int> >\nauto upsample(I1, I2) -> decltype(::cl::sycl::detail::double_width_cast(std::declval<I1>()))":
    arguments:
      - description: ""
        name: hi
        type: I1
      - description: ""
        name: lo
        type: I2
    description: Returns `result[i] = (hi[i] << 8) | lo[i]`
    return: ""
    signature_with_names: "template <typename I1, typename I2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_geninteger8bit<I1>::value && detail::builtin::is_ugeninteger8bit<I2>::value, detail::builtin::is_geninteger16bit<I1>::value && detail::builtin::is_ugeninteger16bit<I2>::value, detail::builtin::is_geninteger32bit<I1>::value && detail::builtin::is_ugeninteger32bit<I2>::value>::value), int> >\nauto upsample(I1 hi, I2 lo) -> decltype(::cl::sycl::detail::double_width_cast(std::declval<I1>()))"
---
