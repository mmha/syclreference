---
layout: function
title: select
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined-in-file: ""
overloads:
  "template <typename T1, typename T2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_genfloath<T1>::value && detail::builtin::is_genshort<T2>::value, detail::builtin::is_genfloath<T1>::value && detail::builtin::is_ugenshort<T2>::value>::value), int> >\nT1 select(T1, T1, T2)":
    arguments:
      - description: ""
        name: a
        type: T1
      - description: ""
        name: b
        type: T1
      - description: ""
        name: c
        type: T2
    description: ""
    return: ""
    signature_with_names: "template <typename T1, typename T2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_genfloath<T1>::value && detail::builtin::is_genshort<T2>::value, detail::builtin::is_genfloath<T1>::value && detail::builtin::is_ugenshort<T2>::value>::value), int> >\nT1 select(T1 a, T1 b, T2 c)"
  "template <typename T1, typename T2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_geninteger<T1>::value && detail::builtin::is_igeninteger<T2>::value, detail::builtin::is_geninteger<T1>::value && detail::builtin::is_ugeninteger<T2>::value, detail::builtin::is_genfloatf<T1>::value && detail::builtin::is_genint<T2>::value, detail::builtin::is_genfloatf<T1>::value && detail::builtin::is_ugenint<T2>::value, detail::builtin::is_genfloatd<T1>::value && detail::builtin::is_igeninteger64bit<T2>::value, detail::builtin::is_genfloatd<T1>::value && detail::builtin::is_ugeninteger64bit<T2>::value>::value), int> >\nT1 select(T1, T1, T2)":
    arguments:
      - description: ""
        name: a
        type: T1
      - description: ""
        name: b
        type: T1
      - description: ""
        name: c
        type: T2
    description: "For each component of a vector type: `result[i] = (MSB of c[i] is set)? b[i] : a[i]` For a scalar type: `result = c ? b : a`. geninteger must have the same number of elements and bits as gentype."
    return: ""
    signature_with_names: "template <typename T1, typename T2, detail::enable_if_t<(computecpp::gsl::or_<detail::builtin::is_geninteger<T1>::value && detail::builtin::is_igeninteger<T2>::value, detail::builtin::is_geninteger<T1>::value && detail::builtin::is_ugeninteger<T2>::value, detail::builtin::is_genfloatf<T1>::value && detail::builtin::is_genint<T2>::value, detail::builtin::is_genfloatf<T1>::value && detail::builtin::is_ugenint<T2>::value, detail::builtin::is_genfloatd<T1>::value && detail::builtin::is_igeninteger64bit<T2>::value, detail::builtin::is_genfloatd<T1>::value && detail::builtin::is_ugeninteger64bit<T2>::value>::value), int> >\nT1 select(T1 a, T1 b, T2 c)"
---
