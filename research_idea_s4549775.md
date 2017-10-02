---
title: Research Idea
author: Hendrik Werner s4549775
date: \today
bibliography: references.bib
fontsize: 12pt
geometry: margin=5em
---

Author=Hendrik Werner

Topic=IPv10

Academic year::2017-18

---

# Topic

I want to investigate whether the proposed IPv10 standard solves the communication and transition problems between IPv4 and IPv6, that it claims to solve.

Should the IPv10 draft be accepted and implemented as a solution to the current communication and transition problems between IPv4 and IPv6?

# Problem

Does IPv10 meet its declared goals?

* Is the proposed solution more efficient than currently used ones?
* Does it allow for communication between all types of hosts?
	* IPv4 / IPv4
	* IPv4 / IPv6
	* IPv6 / IPv4
	* IPv6 / IPv6
* Does it increase flexibility when using DNS?
* Does it solve the transition problem?
* Is it easy to deploy to all Internet connected hosts?

# Relevance

IPv4 is indisputably insufficient for the current Internet landscape. This problem was recognized a long time ago and a new standard was invented called IPv6.

There is the problem of transitioning from one protocol to the other though. Despite ongoing efforts the adoption of IPv6 is not nearly as universal as many had hoped. Currently there are several workarounds in use for reconciling the communication between hosts using different protocols, and to ease the transition.

The Internet is far too complex, big, and diverse to allow for a "switch day" as proposed before. The workarounds are mostly ad hoc, or complex, and don't solve many of the problems. The number of IPv6 hosts is still increasing only very slowly.

The IPv10 proposal claims to solve the communication and transition problems, while being easy to deploy, efficient, and flexible. It is important to test these claims in order to decide whether to officially adopt the standard, and to ultimately finally solve the problems with IPv4 that were identified decades ago.

# Theoretical Background

Both IPv4 [@rfc791] and [IPv6](https://tools.ietf.org/html/rfc2460) were introduced through RFCs (request for comment), which are the usual publication medium for standards by the IETF (Internet engineering task force). The RFCs were proposed and went through several rounds of comments, and changes, until they got accepted and published in their final form.

We want to subject the IPv10 proposal to the same scrutiny, in order to decide whether to adopt it as the new standard Internet protocol. There are several established methods to deal with coexistence, as well as transition of IPv4 and IPv6 hosts. Therefore we not only want to test whether the claims made in the proposal hold up, but also how the new protocol compares to existing solutions, currently deployed.

# Method

The research method we want to use is a case study, in which we transition (some part of) the university network from dual stack to IPv10. We will evaluate the difficulties we encounter on the way, as well as performance improvements in the categories of flexibility, efficiency, as well as ease of deployment.

If this should be necessary, we will also do a survey of members of the C&CZ, to gather additional data about problems occurring after deployment, and in the maintenance phase.

# Literature
