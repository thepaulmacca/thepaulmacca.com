---
title: Kubernetes Certification Resources
date: 2024-10-13
authors:
  - name: Paul McDonald
    link: https://github.com/thepaulmacca
    image: https://github.com/thepaulmacca.png
tags:
  - Kubernetes
  - Certifications
---

In this short post, I'm going to share some resources that you may find useful if you're thinking of pursuing any of the Kubernetes certifications soon. These are what have worked for me and many others.

## Why Get Certified?

Some people don't value certifications all that much, and that's fine - we all have our opinion on them. For me, they provide a structured learning path and an opportunity to learn new skills, which is never a bad thing in this day and age.

I like the Kubernetes certifications in particular as they're performance-based, you can't wing them. You must be proficient in all areas of the curriculum, and regular practice needs to be a part of your study plan.

## Exam Simulator

When you purchase an exam it includes 2 exam simulation attempts, use them. If this is the first time you're taking one of these exams, it really helps you get used to the environment (and believe me, it takes some getting used to).

They're also useful to gauge where your weak areas are, and where to focus. I tend to use the first attempt quite early, and then use the second one a few days before taking the exam.

## Curriculum

Before you get going, have a look at the [curriculum repo](https://github.com/cncf/curriculum) and grab a PDF for the exam you're looking to take.

I tend to like having a local copy to refer to as a reference, to make sure I'm focusing on the right areas.

## Local Cluster

As mentioned earlier, these are performance-based exams - so it goes without saying that you should have a local cluster for learning, practice and experimentation. It will also help build your confidence - you can break/fix whatever you want, when you want, without any time limits being imposed.

I tend to use [kind](https://kind.sigs.k8s.io/), as I find it relatively lightweight and flexible with it's configuration options.

{{< callout type="info" >}}
  If you're looking for an easy way to get started with a cluster, please check out my [k8s-local-cluster](https://github.com/thepaulmacca/k8s-local-cluster) repo.
{{< /callout >}}

{{< callout type="info" >}}
  From the [v.0.24.0 kind release](https://github.com/kubernetes-sigs/kind/releases/tag/v0.24.0) it includes network policy support, so you no longer need to use a CNI plugin like Calico for basic scenarios. I've not managed to get them to work yet though, so have stuck with Calico for now until the issue is resolved.
{{< /callout >}}

## Certified Kubernetes Administrator (CKA)

I found the Udemy [Certified Kubernetes Administrator (CKA) with Practice Tests](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/) course to be the best for this exam. The fact that you also get access to practice tests with it aswell makes it worth the money in my opinion.

### CKA Killer Shell

It's also worth going through the [Killer Shell scenarios](https://killercoda.com/cka). These are free, but have a time limit.

## Certified Kubernetes Application Developer (CKAD)

I found the Udemy [Kubernetes Certified Application Developer (CKAD) with Tests](https://www.udemy.com/course/certified-kubernetes-application-developer/) course to be the best for this exam aswell. Similar to the CKA course, you also get access to practice tests.

### CKAD Killer Shell

Similar to the CKA, it's also worth going through the [Killer Shell scenarios](https://killercoda.com/killer-shell-ckad).

## Certified Kubernetes Security Specialist (CKS)

I've found this exam to be the toughest of them all (it's quite well known for that), and am still yet to pass it. I'm going to keep trying though, but have had to take a step back for now for a bit of a mental break 😅.

The lack of material for this exam is quite surprising compared to the CKA/CKAD given how tough it is, but a lot of people refer to this [YouTube CKS](https://youtu.be/d9xfB5qaOfg?si=xPbBVR9_Pts6kk-p) course by Killer Shell. It's **11 hours** long, so you'll have to break it down into small chunks as there's _a lot_ to take in.

{{< callout type="warning" >}}
  This course hasn't been updated for a while now, and given the [recent changes to the exam](https://training.linuxfoundation.org/cks-program-changes/), you'll only be able to pick out certain parts of it for your study.
{{< /callout >}}

### CKS Killer Shell

You should also go through the [Killer Shell scenarios](https://killercoda.com/killer-shell-cks) for this exam aswell.

### CKS Study Guide

I've also been reading this [study guide by Benjamin Muschko](https://amzn.eu/d/6KReKUL), but i'd say that you need to supplement it with the above YouTube course and plenty of labbing!

## Summary

Preparation is key when studying for these exams - but using these resources, you'll be in a good place. Best of luck on your Kubernetes certification journey!
