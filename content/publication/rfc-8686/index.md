---
title: "Application-Layer Traffic Optimization (ALTO) Cross-Domain Server Discovery"
date: 2020-02-01
publishDate: 2020-04-10T19:26:35.176199Z
categories: ["rfc"]
authors: ["Sebastian Kiesel", "Martin Stiemerling"]
publication_types: ["0"]
abstract: "The goal of Application-Layer Traffic Optimization (ALTO) is to provide guidance to applications that have to select one or several hosts from a set of candidates capable of providing a desired resource. ALTO is realized by a client-server protocol. Before an ALTO client can ask for guidance, it needs to discover one or more ALTO servers that can provide suitable guidance. In some deployment scenarios, in particular if the information about the network topology is partitioned and distributed over several ALTO servers, it may be necessary to discover an ALTO server outside of the ALTO client's own network domain, in order to get appropriate guidance. This document details applicable scenarios, itemizes requirements, and specifies a procedure for ALTO cross-domain server discovery. Technically, the procedure specified in this document takes one IP address or prefix and a U-NAPTR Service Parameter (typically, \"ALTO:https\") as parameters. It performs DNS lookups (for NAPTR resource records in the \"in-addr.arpa.\" or \"ip6.arpa.\" trees) and returns one or more URIs of information resources related to that IP address or prefix."
featured: false
publication: "*RFC Editor*"
url_pdf: "https://rfc-editor.org/rfc/rfc8686.txt"
doi: "10.17487/RFC8686"
---

