---
title: "Toward Optimal Software-Defined Interdomain Routing"
date: 2020-06-01
publishDate: 2020-04-13T15:29:01.061927Z
authors: ["Qiao Xiang", "Jingxuan Zhang", "Kai Gao", "Yeon-sup Lim", "Franck Le", "Geng Li", "Y. Richard Yang"]
publication_types: ["1"]
abstract: "End-to-end route control spanning a set of networks can provide opportunities to both end users to optimize interdomain control and network service providers to increase business offering. BGP, the de facto interdomain routing protocol, provides no programmable control. Recent proposals for interdomain control, such as MIRO, ARROW and SDX, provide more mechanisms and interfaces, but they are only either pointor incremental solutions. In this paper, we provide the first,systematic formulation of thesoftware-defined  internetworking(SDI)model, in which a network exposes a programmable interface to allow clients to define the interdomain routes of the network, just as a traditional SDN switch exposes Openflowor another programmable interface to allow clients to define its next hops, extending SDN from intra-domain control to generic interdomain control. Different from intradomain SDN, which allows complete client control, SDI should also maximize network autonomy, such as by allowing a network to maintain the control of its interdomain export policies, to avoid fundamental violations such as valley routing. We define the optimal  end-to-end  SDIrouting  problem and conduct rigorous analysis to show that the problem is NP-hard. We develop a blackbox optimization algorithm, which leverages Bayesian optimization theory and important properties of interdomain routing algebra, to sample end-to-end routes sequentially and find a near-optimal policy-compliant end-to-end route with a small number of sample routes. We implement a prototype of our optimization algorithm and validate its effectiveness via extensive experiments using real interdomain network topology. Results show that in an interdomain network with over 60000 ASes and over 320000 AS-level links, in 80% experiment cases, the blackbox optimization algorithm can find a near-optimal policy-compliant end-to-end route by sampling less than 33 routes."
featured: false
url_pdf: "/files/papers/sdi-infocom20.pdf"
publication: "*2020 IEEE Conference on Computer Communications (INFOCOM)*"
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- alto-internet
---

