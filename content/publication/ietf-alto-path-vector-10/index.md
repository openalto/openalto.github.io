---
title: "ALTO Extension: Path Vector"
subtitle: "WG Document"
date: 2020-03-01
publishDate: 2020-04-13T21:08:12.334322Z
authors: ["Kai Gao", "Sabine Randriamasy", "Y. Richard Yang", "J. (Jensen) Zhang"]
categories: ["internet-draft"]
publication_types: ["4"]
abstract: "This document is an extension to the base Application-Layer Traffic Optimization protocol [RFC7285]. The current ALTO Cost Services allow applications to obtain cost values on an end-to-end path defined by its source and destination. The present extension provides abstracted information on particular network parts or elements traversed by a path between its source and destination. Examples of such abstracted parts are networks, data centers or links. This is useful for applications whose performance is impacted by particular network parts they traverse or by their properties. Applications having the choice among several connection paths may use this information to select paths accordingly and improve their performance. In particular, they may infer that several paths share common links and prevent traffic bottlenecks by avoiding such paths. This document introduces a new cost type called Path Vector. A Path Vector is an array of entities that each identifies an abstracted representation of a network part and that are called Abstract Network Element (ANE). Each ANE is defined by a set of properties. ANE properties are conveyed by an ALTO information resource called \"Property Map\", that can be packed together with the Path Vectors in a multipart response. They can also be obtained via a separate ALTO request to a Property Map. An ALTO Property Map is an extension to the ALTO protocol, that is specified in another document entitled \"Unified Properties for the ALTO Protocol\" [I-D.ietf-alto-unified-props-new]."
featured: false
publication: "*Internet Engineering Task Force*"
url_pdf: "https://tools.ietf.org/pdf/draft-ietf-alto-path-vector-10.pdf"
---

