---
title: "Add feature - scheduler with warmup each cycle"
link: ""
image: "/images/pytorch-ignite.png"
description: "add warmup duration in CosineAnnealingScheduler and LinearCyclicalScheduler for warmup each cycle"
featured: true
tags: ["PyTorch","DL","PyTorch Ignite","Scheduler"]
fact: ""
weight: 100
sitemap: 
    priority : 0.8
---
<!-- Read More -->
Referring by this [Github Repo](https://github.com/katsura-jp/pytorch-cosine-annealing-with-warmup), I added CosineAnnealingScheduler with warmup each cycle : [PR](https://github.com/pytorch/ignite/pull/3064)

For consistency, I add argument in LinearCyclicalScheduler class while preserving BC(backward compatibility) : [PR](https://github.com/pytorch/ignite/pull/3186)

Also I added test code for above new arguments
