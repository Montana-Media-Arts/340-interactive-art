---
title: Optimization
module: 11
jotted: false
toc: false
math: true
topic: Optimization in TouchDesigner
---

Many of you have no doubt started to run into a significant issue that is inherent with TouchDesigner on lower-level personal computers, that the FPS can really start to drag down.

This occurs when there is too much processing time required on either the CPU or GPU for each frame. What happens is that TD literally needs to take more time between frames to process everything than is possible at 60 FPS. When this occurs, you need to find ways of _optimizing_ your TD network to reduce overhead, and free up resources and processing time.

## Difference Between CPU and GPU

Before we dive into a number of optimization tutorials, I first want to ensure that you understand the difference between a CPU and GPU. The CPU (or central processing unit) is the main processor in your computer and handles calculations for most tasks. It is optimized to work quickly, on a single command at a time. Multi-core CPU's make concurrency of tasks possible, but generally CPU's are intended to do one thing at a time, as quickly as possible. This may include simple math problems (such as $$x X = 1 + 1$$), or tasks such as adding a letter/character to a word document.

Whereas a GPU (or Graphics Processing Unit) is optimize to accomplish parallel processing of multiple similar tasks at the same time. This quality is what makes GPU's important for high-end graphics work, as they are optimized to process large amount of information, such as a graphic on your computer screen.

Each, CPU's and GPU's, serve critical roles within the system that is a modern computer.

**_{ TODO: }_**

For more information please read the following article by NVIDIA, the creators of some of the world's most powerful GPU's.

- [What’s the Difference Between a CPU vs a GPU? - NVIDIA Blog](https://blogs.nvidia.com/blog/2009/12/16/whats-the-difference-between-a-cpu-and-a-gpu/)

## Optimization

The following tutorials give overviews of how to identify where the processing bottleneck is occurring, how to identify whether it is a CPU or GPU problem, and how to reduce processing overhead.

**_{ TODO: }_**

Please read each of the following to help with optimization in TouchDesigner.

- [Optimize - TouchDesigner Documentation](https://docs.derivative.ca/Optimize)
- [Optimizing in TouchDesigner - The Interactive & Immersive HQ](https://interactiveimmersive.io/blog/deployment/optimizing-in-touchdesigner/)
