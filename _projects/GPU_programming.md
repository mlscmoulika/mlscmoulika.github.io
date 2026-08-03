---
title: GPU Programming
layout: default
---
## Overview
This project is my exploration of GPU programming so far. The aim is to understand how to optimise GPU workloads to train large models more efficiently. To achieve this, I want to explore the basics, like matrix addition on GPU and ramp up to advanced topics.

## Topics Covered:

* **GPU Profiling** - GPU profiling is the process of analysing the performance of GPU while running a function, which helps in tackling bottlenecks and improving GPU performance. Two such in-built profilers explored during this project are, `torch.profiler` and `torch.cuda.Event`. The advantage of using `torch.profiler` is that it gives a detailed breakdown of the time taken by each operation, while `torch.cuda.Event` only gives the total time taken for a specific operation. However, `torch.profiler` can introduce some overhead, so for very small operations, the timing may not be accurate. [Ref. link](https://www.youtube.com/watch?v=LuhJEEJQgUM)
* **LeetGPU** - [LeetGPU](https://leetgpu.com/) is a coding platform, similar to [LeetCode](https://leetcode.com/), but for GPU programming. `triton` and `jax` were used to answer the questions. If, `cuda` provides low-level control using C/C++, then `triton` is a high-level, python based library that automates memory and thread management([ref](https://www.youtube.com/watch?v=DdTsX6DQk24)). `Jax` is a python based library for array oriented numerical computations. The sources I have referred to so far are:
    * [GPU MODE](https://www.youtube.com/@GPUMODE)
    * [Working of GPU](https://www.youtube.com/watch?v=h9Z4oGN89MU)
    * [GPU vs CPU](https://www.youtube.com/watch?v=Axd50ew4pco&t=96s)

## Motivation
GPU programming is an important skill in domains like HPC, computer graphics, ML and many more. Based on my interests I see myself exploring roles as an ML Engineer or researcher or related roles. Through this project, I want to develop a deep understanding of GPU programming and become comfortable using GPU to optimise the training of my models. 

## Key learnings and takeaways so far:
* GPU Profiling
* Easy level LeetGPU questions

## Repo Link:
[GitHub link](https://github.com/mlscmoulika/gpu_testing)

## Is it ongoing/completed?
Ongoing! Feel free to tag along to collaborate