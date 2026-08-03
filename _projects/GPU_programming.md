---
title: GPU Programming
layout: default
---
## What is this project about?
This project is my exploration on GPU programming, I have done so far. Following are the topics:
* **GPU Profiling** - GPU profiling is to study the performance of a code on GPU. These techniques help in optimising the code which is supposed to run on a GPU, by analysing the aspects like speed, memory usage etc. The code includes, `torch.profiler` and `torch.cuda.Event`. Note : advatage of using `torch.profiler` is that it gives you a detailed breakdown of the time taken by each operation, while `torch.cuda.Event` only gives you the total time taken for a specific operation. However, `torch.profiler` can introduce some overhead, so for very small operations, the timing may not be accurate. [Ref. link](https://www.youtube.com/watch?v=LuhJEEJQgUM)
* **LeetGPU** - I got a chance to explore [LeetGPU](https://leetgpu.com/), which is just like [LeetCode](https://leetcode.com/), but for GPU programming. I got a chance to venture into `triton` while exploring this aspect. If `Cuda` is the high end Camera, then, `Triton` is like a high end smartphone camera. As in that, in `triton`, you can't control everything here but get good performance here. On the other hand with `cuda`, you can control many things and get better performance, but you have to write it in C programming language([ref](https://www.youtube.com/watch?v=DdTsX6DQk24)). I tried to solve a few questions using `triton` and `jax`. This part of the project helped me understand, how different is CPU and GPU programming are. I did struggle a bit to get some hang of it. The sources I have referred to so far are:
    * [GPU MODE](https://www.youtube.com/@GPUMODE)
    * [Working of GPU](https://www.youtube.com/watch?v=h9Z4oGN89MU)
    * [GPU vs CPU](https://www.youtube.com/watch?v=Axd50ew4pco&t=96s)

## Why did I do it?
I see that I am interested to apply for ML Engineer and/or related roles. And ML Engineers when they deal with larger models or bigger datasets, use GPUs to keep the things going. Though there are a couple of things taken care off by the Cloud services that we make use of day to day. I just wanted to take it a step further and learn how to use GPUs efficiently. I am still learning the basics, but I want to take myself to a stage wherein I feel comfortable using GPU to optimise the training of my models. 

## Key learnings and takeaways so far:
* GPU Profiling
* Easy level LeetGPU questions

## Repo Link:
[Github link](https://github.com/mlscmoulika/gpu_testing)

## Is it ongoing/completed?
Ongoing! Feel free to tag along to collaborate