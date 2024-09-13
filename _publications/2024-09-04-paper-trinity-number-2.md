---
title: "Trinity: A General Purpose FHE Accelerator"
collection: publications
permalink: /publications/2024-09-04-paper-trinity-number-2
excerpt: 'In this paper, we present the first multi-modal FHE accelerator based on a unified architecture, which efficiently supports CKKS, TFHE, and their conversion scheme within a single accelerator.'
date: 2024-09-04
venue: 'MICRO'
paperurl: ''
citation: '<u><b>Xianglong Deng</b></u>, Shengyu Fan, Zhicheng Hu, Zhuoyu Tian, Zihao Yang, Jiangrui Yu, Dingyuan Cao, Dan Meng, Rui Hou, Meng Li, Qian Lou, Mingzhe Zhang. 57th IEEE/ACM International Symposium on Microarchitecture. MICRO 2024'
---

In this paper, we present the first multi-modal FHE accelerator based on a unified architecture, which efficiently supports CKKS, TFHE, and their conversion scheme within a single accelerator. To achieve this goal, we first analyze the theoretical foundations of the aforementioned schemes and highlight their composition from a finite number of arithmetic kernels. Then, we investigate the challenges for efficiently supporting these kernels within a unified architecture, which include 1) concurrent support for NTT and FFT, 2) maintaining high hardware utilization across various polynomial lengths, and 3) ensuring consistent performance across diverse arithmetic kernels. To tackle these challenges, we propose a novel FHE accelerator named Trinity, which incorporates algorithm optimizations, hardware component reuse, and dynamic workload scheduling to enhance the acceleration of CKKS, TFHE, and their conversion scheme. By adaptive select the proper allocation of components for NTT and MAC, Trinity maintains high utilization across NTTs with various polynomial lengths and imbalanced arithmetic workloads. The experiment results show that, for the pure CKKS and TFHE workloads, the performance of our Trinity outperforms the state-of-the-art accelerator for CKKS (SHARP) and TFHE (Morphling) by 1.49 $\times$ and 4.23 $\times$, respectively. Moreover, Trinity achieves 919.3 $\times$ performance improvement for the FHE-conversion scheme over the CPU-based implementation. 
