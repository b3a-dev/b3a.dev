---
title: "Network security for microservices with eBPF"
date: 2019-04-15T12:27:38+06:00
description : "Network security for microservices with eBPF"
type: post
image: images/blog/ebpf-post-2.png
author: Beatriz Martínez
mediumlink: https://medium.com/@beatrizmrg/network-security-for-microservices-with-ebpf-bis-478b40e7befa
tags: ["Linux", "Ebpf", "Microservices", "Networking", "Cilium"]
---
Several open-source Kubernetes tools are already using eBPF. Mainly related to networking, monitoring, and security.
The intention of this post is not to provide complete coverage of all eBPF aspects, but rather tries to be a informational starting point guide, from the understanding of Linux kernel BPF concept, through the advantages and features that brings to microservices environments, to some known tools that currently make use of it, such Cilium or Weave.

Understanding eBPF

Berkely Packet Filters, short BPF, is an instruction set architecture that was first introduced by Steven McCanne and Van Jacobso in 1992, as a generic packet filtering solution for applications such as tcpdump, that was the first use case, and is long present in Linux Kernels.

BPF can be regarded as a minimalistic “virtual” machine construct. The machine it abstracts has only a few registers, stack space, an implicit program counter and a helper function concept that allows for side effects with the rest of the kernel.