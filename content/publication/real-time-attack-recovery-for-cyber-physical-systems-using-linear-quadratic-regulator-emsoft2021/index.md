---
title: Real-Time Attack-Recovery for Cyber-Physical Systems using
  Linear-Quadratic Regulator(EMSOFT2021)
publication_types:
  - "2"
authors:
  - Lin Zhang
  - Xin Chen
  - Fanxin Kong
  - and Alvaro A. Cardenas
publication: The 41st IEEE Real-Time Systems Symposium, 2020
abstract: The increasing autonomy and connectivity in cyber-physical systems
  (CPS) come with new security vulnerabilities that are easily exploitable by
  malicious attackers to spoof a system to perform dangerous actions. While the
  vast majority of existing works focus on attack prevention and detection, the
  key question is “what to do after detecting an attack?”. This problem attracts
  fairly rare attention though its significance is emphasized by the need to
  mitigate or even eliminate attack impacts on a system. In this article, we
  study this attack response problem and propose novel real-time recovery for
  securing CPS. First, this work’s core component is a recovery control
  calculator using a Linear-Quadratic Regulator (LQR) with timing and safety
  constraints. This component can smoothly steer back a physical system under
  control to a target state set before a safe deadline and maintain the system
  state in the set once it is driven to it. We further propose an Alternating
  Direction Method of Multipliers (ADMM) based algorithm that can fast solve the
  LQR-based recovery problem. Second, supporting components for the attack
  recovery computation include a checkpointer, a state reconstructor, and a
  deadline estimator. To realize these components respectively, we propose (i) a
  sliding-window-based checkpointing protocol that governs sufficient
  trustworthy data, (ii) a state reconstruction approach that uses the
  checkpointed data to estimate the current system state, and (iii) a
  reachability-based approach to conservatively estimate a safe deadline.
  Finally, we implement our approach and demonstrate its effectiveness in
  dealing with totally 15 experimental scenarios which are designed based on 5
  CPS simulators and 3 types of sensor attacks.
draft: false
featured: false
tags:
  - Real-Time Attack-Recovery
  - Cyber-Physical Systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-20T15:03:21.638Z
---
