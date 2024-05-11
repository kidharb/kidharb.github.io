---
layout: post
title: Performance fix https://github.com/f3d-app/f3d/issues/1348
date: 2024-05-11 17:r301:00
description: Documenting the steps while working on this issue
tags: formatting code bugfixes
categories: opensource
---

I am a noobie contributer to [f3d](https://f3d.github.com). My first contribution (and first ever open source contribution) was [documentation](https://github.com/f3d-app/f3d/pull/1160) followed by a [feature](https://github.com/f3d-app/f3d/pull/1235) and now this startup performance [issue](https://github.com/f3d-app/f3d/issues/1348).
My intention is to document the steps I took to solve this issue.

Step 1 - Get more information
When I tackle any problem, I always start of with finding out as much as I can about the issue. It is useful to get answers to the following: -

1. When did the issue first start?
2. How do you reproduce the issue?
3. What is the reproducibility rate?
4. Does the problem happen in other environments / platforms?

A good defect will contain all of the above and prehaps more. Since I do not trust anyone, including myself, my first piece of work is to verify the information provided. 
For this issue the following information was provided

1. When did the first issue first start? v2.4 (But maybe it was only picked up on this version)
2. How do you reproduce the issue? The steps are clear
3. What is the reproducibility rate? Judging from the steps to reproduce I would assume this is a 100% reproducible issue
4. Does the problem happen in other environments / platforms? The reporter is unsure so maybe it is something that can be confirmed, if it is easy enough.

When I first started my professional career, my first manager (and mentor) taught me something that stuck...do the easy tests first. So lets try and reproduce the issue.
