---
title: "ALTO Performance Cost Metrics"
subtitle: "WG Document"
date: 2020-03-01
publishDate: 2020-04-13T21:08:12.335319Z
authors: ["Qin Wu", "Y. Richard Yang", "Dhruv Dhody", "Sabine Randriamasy", "Luis M. Contreras"]
categories: ["internet-draft"]
publication_types: ["4"]
abstract: "Cost metric is a basic concept in Application-Layer Traffic Optimization (ALTO), and is used in basic ALTO services including both the cost map service and the endpoint cost service. Different applications may use different cost metrics, but the ALTO base protocol [RFC7285] documents only one single cost metric, i.e., the generic \"routingcost\" metric; see Sec. 14.2 of [RFC7285]. Hence, if the resource consumer of an application prefers a resource provider that offers low-delay delivery to the resource consumer, the base protocol does not define the cost metric to be used. ALTO cost metrics can be generic metrics and this document focuses on network performance metrics, including network delay, jitter, packet loss, hop count, and bandwidth. When using an ALTO performance metric, an application may need additional contextual information beyond the metric value. For example, whether the metric is an estimation based on measurements or a service-level agreement (SLA) can define the meaning of a performance metric. Hence, this document introduces an additional \"cost-context\" field to the ALTO \"cost-type\" field to convey such information. To report an estimated value of a performance metric, the ALTO server may derive and aggregate from routing protocols with different granularity and scope, such as BGP-LS, OSPF-TE and ISIS-TE, or from end-to-end traffic management tools. These metrics may then be exposed by an ALTO Server to allow applications to determine \"where\" to connect based on network performance criteria."
featured: false
publication: "*Internet Engineering Task Force*"
url_pdf: "https://tools.ietf.org/pdf/draft-ietf-alto-performance-metrics-09.pdf"
---

