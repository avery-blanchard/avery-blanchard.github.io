---

permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
redirect_from: 
  - /work/
---

## Container IMA using eBPF **advised by Professor Jason Nieh** 
### Columbia University + Red Hat
With the ubiquity of container-based virtualization, the ability to ensure trust in a container is a pertinent security issue. The mechanism in the Linux kernel for measuring integrity within a system, Integrity Measurement Architecture IMA, does not support Linux containers. This leaves a substantial gap in container integrity and trust. I present a solution through implementing a run-time solution for continuous integrity monitoring of Linux containers without changes to the kernel. I aim to extend the Integrity Measurement Architecture to Linux containers through the use of a loadable kernel module and eBPF. This projects explores the design and implementation of using eBPF to measure container integrity.

## Encrypted TAO
### Columbia University COMSE6998
A privacy preserving graph data store. Implemented Order Preserving Encryption OPE in Rust. Encrypted queries using OPE and symmetric encryption. \
Open source [repository](https://github.com/encrypted-tao/encrypted-tao) 

## Digital Cooking **advised by Professor Hod Lipson**
### Columbia University's Creative Machines Lab
The goal of the Digital Cooking Team at the Creative Machines Lab is to design a 3D printer capable of fabricating edible items through the computer-guided deposition of ingredients. The design and implementation of this printer's software is in C++ and Python.

## Robotic Grasping System 
### Columbia University COMSW4733
A project focusing on deep learning, semantic parsing, ICP and RRT algorithms to build a self-improving robotic grasping system. Image segmentation is used for object detection, the ICP algorithm is used to estimate object pose, and path planning is done using the RRT algorithm.