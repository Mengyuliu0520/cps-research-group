---
title: Utilization Control and Optimization of Real-Time Embedded Systems
publication_types:
  - "5"
authors:
  - Xue Liu
  - Xi Chen
  - Fanxin Kong
doi: 10.1561/1000000042
abstract: >+
  Real-time embedded systems have been widely deployed in mission-critical
  applications, such as avionics mission computing, highway traffic control,
  remote patient monitoring, wireless communications, navigation, etc. These
  applications always require their real-time and embedded components to work in
  open and unpredictable environments, where workload is volatile and unknown.
  In order to guarantee the temporal correctness and avoid severe
  underutilization or overload, it is of vital significance to measure, control,
  and optimize the processor utilization adaptively. A key challenge in this
  mission is to meet real-time requirements even when the workload cannot be
  accurately characterized a priori. Traditional approaches of worst-case
  analysis may cause underutilization of resources, while Model Predictive
  Control (MPC) based approaches may suffer severe performance deterioration
  when large estimation errors exist. To address this challenging problem and
  provide better system performance, we have developed several important online
  adaptive optimal control approaches based on advanced control techniques. Our
  approaches adopt Recursive Least Square (RLS) based model identification and
  Linear Quadratic (LQ) optimal controllers to guarantee that the systems are
  neither overloaded, nor underloaded. These proposed approaches, as well as the
  associated tools, can quickly adapt to volatile workload changes to provide
  stable system performance. To minimize the impact of modeling errors, we adopt
  the Adaptive Critic Design (ACD) technique and develop an improved solution
  that requires little information of the system model. To deal with the
  discrete task rates, we further propose to utilize the frequency scaling
  technique to assist the utilization control and optimization. The
  computational overhead of centralized approaches explodes as the scale of
  systems increases. To ensure system scalability and global stability,
  decentralized control and optimization approaches are desired. We leverage an
  efficient decoupling technique and derive several distributed approaches.
  These approaches adopt one feedback loop to adjust the task rate, and apply
  another feedback loop to control the CPU frequency asynchronously. As these
  two manipulated variables (i.e., the CPU frequency and task rate) contribute
  to the system performance together with a strong coupling, asynchronous
  control approaches may not be able to achieve the optimal performance. To
  handle this coupling, we further develop a synchronous rate and frequency
  control and optimization approach. This approach jointly and synchronously
  adjusts rate and frequency settings, and achieves enhanced system performance.
  All the aforementioned approaches are based on certain mathematical models.
  However, it is sometimes hard to develop an exact model to characterize a
  real-time embedded system. In order to deal with this issue, we further
  develop a model-free utilization control and optimization solution by applying
  the fuzzy logic control theory. The application of this theory allows us to
  achieve the desired performance in a nonlinear dynamic system without a
  specific system model. The proposed fuzzy utilization control approaches are
  stable and fast-converging, and achieve smaller tracking errors than
  model-based approaches.

draft: false
featured: false
tags:
  - Optimal Control
  - Control Applications
  - Performance
  - Adaptive control and signal processing
  - Distributed control and optimization of distribution networks
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: >-
  Real-time embedded systems are widely deployed in mission-critical
  applications, such as avionics mission computing, highway traffic control,
  remote patient monitoring, wireless communications, navigation, etc. These
  applications always require their real-time and embedded components to work in
  open and unpredictable environments, where workload is volatile and unknown.
  In order to guarantee the temporal correctness and avoid severe
  underutilization or overload, it is of vital significance to measure, control,
  and optimize the processor utilization adaptively.


  This monograph examines utilization control and optimization in real-time embedded systems. In many practical real-time embedded applications, it is desired to keep the processors’ utilizations at the schedulable upper bounds. In this way, the systems deliver their best Quality of Service (QoS), and, at the same time, all real-time tasks remain schedulable. In order to achieve this goal, the authors present several effective solutions that adaptively adjust task rates and/or processor frequencies to enforce the desired utilization. Feedback control and optimization techniques have been leveraged to ensure that a system is neither overloaded nor underutilized.
date: 2021-11-14T22:15:01.473Z
---
