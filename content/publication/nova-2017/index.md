---
title: "NOVA: Towards on-demand equivalent network view abstraction for network optimization"
date: 2017-06-01
publishDate: 2020-04-13T15:29:01.052949Z
authors: ["Kai Gao", "Qiao Xiang", "Xin Wang", "Yang Richard Yang", "Jun Bi"]
publication_types: ["1"]
abstract: "As many applications today migrate to distributed computing and cloud platforms, their user experience depends heavily on network performance. Software Defined Networking (SDN) makes it possible to obtain a global view of the network, introducing the new paradigm of developing adaptive applications with network views. A naive approach of realizing the paradigm, such as distributing the whole network view to applications, is not practical due to scalability and privacy concerns. Existing approaches providing network abstractions are limited to special cases, such as bottlenecks exist only at networks edges, resulting in potentially suboptimal or infeasible decisions. In this paper, we introduce a novel, on-demand network abstraction service that provides an abstract network view supporting not only accurate end-to-end QoS metrics, which satisfy the requirements of many peer-to-peer applications, but also multi-flow correlation, which is essential for bandwidth-sensitive applications containing many flows to conduct global network optimization. We prove that our abstract view is equivalent to the original network view, in the sense that applications can make the same optimal decision as with the complete information. Our evaluations demonstrate that the abstraction guarantees feasibility and optimality for network optimizations and protects the network service providers' privacy. Our evaluations also show that the service can be implemented efficiently; for example, for an extreme large network with 30,000 links and abstraction requests containing 3,000 flows, an abstract network view can be computed in less than one second."
featured: false
publication: "*2017 IEEE/ACM 25th International Symposium on Quality of Service (IWQoS)*"
url_slides: "/files/slides/nova-iwqos17-slides.pdf"
url_pdf: "/files/papers/nova-iwqos17.pdf"
doi: "10.1109/IWQoS.2017.7969117"
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- multidomain-alto
---

