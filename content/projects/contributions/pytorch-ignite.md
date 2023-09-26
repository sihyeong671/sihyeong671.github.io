---
title: "PyTorch Ignite"
link: ""
image: "/images/pytorch-ignite.png"
description: "PyTorch Ignite contribution"
featured: true
tags: ["PyTorch","DL","PyTorch Ignite","Scheduler"]
fact: ""
weight: 100
sitemap: 
    priority : 0.8
---
<!-- Read More -->
Addressed pretty significant page load performance issue founde in larger deployments. Eliminates uses of intensive backend query, replacing it with an asynchronous API call against a lucene index. This change reduces page load from from 2+ minutes to nearly instant, with an incredibly responsive UI.
