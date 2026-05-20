---
title: "Knowledge Distillation in Super-Resolution for Jet Classification"
permalink: /internship-super-resolution/
author_profile: true
---

**Brown University**

[GitHub](https://github.com/pabulblues/Super-Resolution-using-Knowledge-Distillation.git){: .btn .btn--info}

---

## Abstract

Deep learning models for high-energy physics face a trade-off between accuracy and computational cost, particularly when processing high-resolution jet images at scale. We explore the use of super-resolution and knowledge distillation to bridge this gap: a high-resolution teacher network is trained on full-detail jet images, and its knowledge is distilled into a lightweight student model that operates on low-resolution inputs upsampled via ESRGAN. This approach allows the student to recover fine-grained jet substructure features without the cost of processing high-resolution data directly. We design and evaluate CNN-based architectures across multiple resolution settings and construct multi-resolution datasets to benchmark the distillation pipeline. Our results demonstrate that knowledge distillation with super-resolution upsampling can maintain competitive classification performance while significantly reducing model complexity, offering a practical path toward scalable jet tagging on large physics datasets.

---

## Summary

I worked on applying super-resolution and knowledge distillation techniques to jet classification tasks. My work involved designing CNN-based models for high and low resolution inputs, implementing ESRGAN super-resolution model, and preparing multi-resolution datasets. The goal is to compress models while maintaining performance and improving scalability on large physics datasets.
