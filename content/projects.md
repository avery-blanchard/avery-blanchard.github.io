---

permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
redirect_from: 
  - /work/
---

## Container IMA using eBPF **advised by Professor Jason Nieh** 
### Columbia University
Containers are pervasive within computing infrastructure due to their agility and scalability. These isolated groups of processes exist through operating-systems level virtualization, and due to the shared nature of the operating system's kernel, security is a pertinent consideration for container development. The ability to measure and monitor the integrity of containers running on the system fills a gap in observability, trust, and security. However, the mechanism in the Linux kernel for measuring integrity within a system, Integrity Measurement Architecture IMA, does not support Linux containers. This project leverages the kernel's existing support of eBPF to extend the Linux Integrity Measurement Architecture to containers without changes to the host operating system. 
[Project github](https://github.com/avery-blanchard/container-ima)

## Encrypted TAO
### Columbia University COMSE6998
A privacy preserving graph data store. The project ported Order Preserving Encryption OPE to Rust to provide range queries over encrypted data. Queries were encrypted using OPE and symmetric encryption. 
[Project github](https://github.com/encrypted-tao/encrypted-tao)

## Digital Cooking **advised by Professor Hod Lipson**
### Columbia University's Creative Machines Lab
The goal of the Digital Cooking Team at the Creative Machines Lab is to design a 3D printer capable of fabricating edible items through the computer-guided deposition of ingredients. The design and implementation of this printer's software is in C++ and Python.

## Robotic Grasping System 
### Columbia University COMSW4733
A project focusing on deep learning, semantic parsing, ICP and RRT algorithms to build a self-improving robotic grasping system. Image segmentation is used for object detection, the ICP algorithm is used to estimate object pose, and path planning is done using the RRT algorithm.