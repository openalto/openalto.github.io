---
title: "SFP: Toward Interdomain Routing for SDN Networks"
date: 2018-01-01
publishDate: 2020-04-13T15:29:01.054947Z
authors: ["Qiao Xiang", "Chin Guok", "Franck Le", "John MacAuley", "Harvey Newman", "Y. Richard Yang"]
publication_types: ["1"]
abstract: "Interdomain routing using BGP is widely deployed and well understood. The deployment of SDN in BGP domain networks, however, has not been systematically studied. In this paper, we first show that the use-announcement inconsistency is a fundamental mismatch in such a deployment, leading to serious issues including unnecessary blackholes, unnecessary reduced reachability, and permanent forwarding loops. We then design SFP, the first fine-grained interdomain routing protocol that extends BGP with fine-grained routing, eliminating the aforementioned mismatch. We develop two novel techniques, automatic receiver filtering and on-demand information dissemination, to address the scalability issue brought by fine-grained routing. Evaluating SFP using real network topologies and traces for intended settings, which are not global Internet but tens of collaborative domains, we show that SFP can reduce the amount of traffic affected by blackholes and loops by more than 50%, and that our proposed techniques can reduce the amount of signaling between ASes by 3 orders of magnitude compared with naive fine-grained routing."
featured: false
publication: "*Proceedings of the ACM SIGCOMM 2018 Conference on Posters and Demos  - SIGCOMM '18*"
url_pdf: "/files/papers/sfp-sigcomm18.pdf"
doi: "10.1145/3234200.3234207"
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- multidomain-alto
- alto-internet
---

