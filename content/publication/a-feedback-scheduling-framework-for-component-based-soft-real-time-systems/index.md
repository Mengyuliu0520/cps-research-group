---
title: A Feedback Scheduling Framework for Component-Based Soft Real-Time Systems
publication_types:
  - "1"
authors:
  - Nima Khalilzad
  - Fanxin Kong
  - Xue Liu
  - Moris Behnam and Thomas Nolte
doi: 10.1109/RTAS.2015.7108441
publication: "The 21st IEEE Real-Time and Embedded Technology and Applications
  Symposium (RTAS), 2015, pp. 182-193. (Acceptance rate: 21.9%)"
publication_short: IEEE
abstract: Component-based software systems with real-time requirements are often
  scheduled using processor reservation techniques. Such techniques have mainly
  evolved around hard real-time systems in which worst-case resource demands are
  considered for the reservations. In soft real-time systems, reserv- ing the
  processors based on the worst-case demands results in unnecessary
  over-allocations. In this paper, targeting soft real-time systems running on
  multiprocessor platforms, we focus on components for which processor demand
  varies during run-time. We propose a feedback scheduling framework where
  processor reservations are used for scheduling components. The reservation
  bandwidths as well as the reservation periods are adapted using MIMO LQR
  controllers. We provide an allocation mechanism for distributing components
  over processors. The proposed framework is implemented in the TrueTime
  simulation tool for system identification. We use a case study to investigate
  the performance of our framework in the simulation tool. Finally, the
  framework is implemented in the Linux kernel for practical evaluations. The
  evaluation results suggest that the framework can efficiently adapt the
  reservation parameters during run-time by imposing negligible overhead.
draft: false
featured: false
tags:
  - Bandwidth
  - Real-time systems
  - Processor scheduling
  - Adaptation models
  - Resource management
  - MIMO
  - Servers
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-11-14T21:35:42.827Z
---
