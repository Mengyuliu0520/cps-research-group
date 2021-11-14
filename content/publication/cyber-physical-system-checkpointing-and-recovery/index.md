---
title: Cyber-Physical System Checkpointing and Recovery
publication_types:
  - "1"
authors:
  - Fanxin Kong
  - Meng Xu
  - James Weimer
  - Oleg Sokolsky
  - and Insup Lee
doi: 10.1109/ICCPS.2018.00011
publication: 2018 ACM/IEEE 9th International Conference on Cyber-Physical Systems (ICCPS)
publication_short: IEEE
abstract: Transitioning to more open architectures has been making
  Cyber-Physical Systems (CPS) vulnerable to malicious attacks that are beyond
  the conventional cyber attacks. This paper studies attack-resilience
  enhancement for a system under emerging attacks in the environment of the
  controller. An effective way to address this problem is to make system state
  estimation accurate enough for control regardless of the compromised
  components. This work follows this way and develops a procedure named CPS
  checkpointing and recovery, which leverages historical data to recover failed
  system states. Specially, we first propose a new concept of physical-state
  recovery. The essential operation is defined as rolling the system forward
  starting from a consistent historical system state. Second, we design a
  checkpointing protocol that defines how to record system states for the
  recovery. The protocol introduces a sliding window that accommodates
  attack-detection delay to improve the correctness of stored states. Third, we
  present a use case of CPS checkpointing and recovery that deals with
  compromised sensor measurements. At last, we evaluate our design through
  conducting simulator-based experiments and illustrating the use of our design
  with an unmanned vehicle case study.
draft: false
featured: false
tags:
  - Task analysis
  - Checkpointing
  - Cyber-physical systems
  - Protocols
  - Synchronization
  - Delays
  - Security
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-11-14T21:03:51.813Z
---
