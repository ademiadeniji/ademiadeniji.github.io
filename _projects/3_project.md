---
layout: post
title: CSM Neural Radiance Field Foundation Model
description: March 2024
img:
importance: 1
category: work
giscus_comments: false
---

I helped train and scale CSM's [Neural Radiance Field (NeRF) Foundation Model](https://www.csm.ai/blog/image-to-3d-in-seconds-is-now-better-than-ever), a 2D-native NeRF model that reconstructs 3D occupancy fields from single image input in <1 minute. This model plugs into a slower refinement process based on Score Distillation Sampling {% cite poole2022dreamfusiontextto3dusing2d %}, which helped grow CSM to over 300k+ users.
