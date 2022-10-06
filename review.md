# Review

## Info

Reviewer Name: Ben Harris (bbh3)

Paper Title: Container-based OS Virtualization

## Summary

### Problem and Why We Care

Virtualizing OS is importnt for customizing environments, isolating programs, and increasing replicability.

### Gap in Current Approaches

Hypervisors create a full OS instance for each VM. 

### Hypothesis, Key Idea, or Main Claim

By sharing a kernel instance, theoretically container-based OS virtualization could get higher performance.

### Method for Proving the Claim

The authors examined a popular hypervisor (Xen) and popular COS system (VServer).

### Method for Evaluating

The authors compared the benchmarks to pure Linux instance.

### Contributions: What We Take Away

In most instances, the COS outperformed the VMM significant margins (especially regarding I/O tasks).

## Pros (3-6 bullets)

- COS had much less overhead
- COS was significantly better at scalability testing

## Cons (3-6 bullets)

- COS doesn't have multikernel
- COS lacks fault isolation

### What is Your Analysis of the Proposed?

I thought this paper was a pretty gerat introduction to COS. It was written at a time when the tech was pretty established, had detailed breakdowns of how VServer works, and then compared to the previous virtual os standard (hypervisors).

## Details Comments, Observations, Questions

Questions on main page. 

Just think this is really cool. Feel like I finally understand VMs, Docker and Kubernetes at a level youtube never could've taught me.


