---
title: "ORSAP: Abstracting routing state on demand"
date: 2016-11-01
publishDate: 2020-04-13T15:29:01.052119Z
authors: ["Kai Gao", "Chen Gu", "Qiao Xiang", "Xin Wang", "Y. Richard Yang", "Jun Bi"]
publication_types: ["1"]
abstract: "Providing an interface for network applications to access network state, Software-Defined Networking (SDN) northbound API protocol is the foundation for the development of programmable networks with adaptive applications. However, with the growing network scale and applications' need for routing state at multi-domain level, feeding complete routing states to applications would jeopardize their scalability and network providers' privacy. Thus a good routing state abstraction is needed, which must be on-demand so that different applications can receive customized abstract state suiting their needs. Moreover, it must be minimal and equivalent, i.e., containing all the necessary information for applications to make decisions as the complete state does with no redundancy. Current routing state abstractions are not on-demand, and adopt extreme aggregation approaches (e.g., the big switch) to provide a minimal abstraction with the price of severe information loss. For instance, bottleneck links shared between flows are concealed, leading applications to make sub-optimal decisions. In this paper, we design ORSAP, the first on-demand routing state abstraction protocol, through which network applications can describe their demands while Internet service providers can provide the on-demand minimal equivalent routing state accordingly. ORSAP ensures applications' scalability, protects network providers' privacy, and significantly reduces the traffic to disseminate the information. Experiments show that with ORSAP and the abstraction engine we introduced in this paper, one can achieve a state abstraction ratio of up to 60% with an extremely low computation time even with large networks and complex application queries."
featured: false
publication: "*2016 IEEE 24th International Conference on Network Protocols (ICNP)*"
url_pdf: "/files/papers/rsa-icnp16-poster.pdf"
doi: "10.1109/ICNP.2016.7784454"
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- multidomain-alto
---

