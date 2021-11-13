---
title: "Recovery-by-Learning: Restoring Autonomous Cyber-physical Systems
  from   Sensor Attacks(RTCSA2021)"
publication_types:
  - "2"
authors:
  - Francis Akowuah
  - Romesh Prasad
  - Carlos Espinoza
  - and Fanxin Kong
doi: 10.1109/RTCSA52859.2021.00015
publication: " 2021 IEEE 27th International Conference on Embedded and Real-Time
  Computing Systems and Applications (RTCSA)"
publication_short: IEEE
abstract: "Autonomous cyber-physical systems (CPS) are susceptible to
  non-invasive physical attacks such as sensor spoofing attacks that are beyond
  the classical cybersecurity domain. These attacks have motivated numerous
  research efforts on attack detection, but little attention on what to do after
  detecting an attack. The importance of attack recovery is emphasized by the
  need to mitigate the attack’s impact on a system and restore it to continue
  functioning. There are only a few works addressing attack recovery, but they
  all rely on prior knowledge of system dynamics. To overcome this limitation,
  we propose Recovery-by-Learning, a data-driven attack recovery framework that
  restores CPS from sensor attacks. The framework leverages natural redundancy
  among heterogeneous sensors and historical data for attack recovery.
  Specially, the framework consists of two major components: state predictor and
  data checkpointer. First, the predictor is triggered to estimate systems
  states after the detection of an attack. We propose a deep learning-based
  prediction model that exploits the temporal correlation among heterogeneous
  sensors. Second, the checkpointer executes when no attack is detected. We
  propose a double sliding window based checkpointing protocol to remove
  compromised data and keep trustful data as input to the state predictor.
  Third, we implement and evaluate the effectiveness of our framework using a
  realistic data set and a ground vehicle simulator. The results show that our
  method restores a system to continue functioning in presence of sensor
  attacks."
draft: false
featured: false
tags:
  - Checkpointing
  - Deep learning
  - Protocols
  - System dynamics
  - Redundancy
  - Cyber-physical systems
  - Predictive models
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-11-13T05:48:57.506Z
---
