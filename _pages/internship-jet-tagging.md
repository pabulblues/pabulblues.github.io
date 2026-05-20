---
title: "Explainability in Graph Neural Networks for Jet Tagging"
permalink: /internship-jet-tagging/
author_profile: true
---

**IIT Kanpur** | *2026 Annual HEP Conference IITK*

[View on arXiv](https://arxiv.org/abs/2604.25885v1){: .btn .btn--info} &nbsp; [GitHub](https://github.com/pabulblues/Explainability-in-GNN-for-Jet-Tagging.git){: .btn .btn--info}

---

## Abstract

Graph neural networks such as ParticleNet and transformer based networks on point clouds such as ParticleTransformer achieve state-of-the-art performance on jet tagging benchmarks at the Large Hadron Collider, yet the physical reasoning behind their predictions remains opaque. We present different methods, i.e. perturbation-based (GNNExplainer), Shapley-value-based (GNNShap), and gradient-based (GRADCam); adapted to operate on LundNet's Lund-plane graph representation. Leveraging the fact that each node in the Lund plane corresponds to a physically meaningful parton splitting, we construct Monte Carlo truth explanation masks and introduce a physics-informed evaluation framework that goes beyond standard fidelity metrics. We perform the analysis in three transverse-momentum bins (p<sub>T</sub>∈[500,700], [800,1000], and the inclusive region [500,1000] GeV), revealing how explanation quality and focus shift between non-perturbative and perturbative regimes. We further quantify the correlation between explainer-assigned node importance and classical jet substructure observables -- N-subjettiness ratios τ<sub>21</sub> and τ<sub>32</sub> and the energy correlation functions -- establishing the degree to which the model has learned known QCD features. We find that overall the weight assigned by explainability methods has a correlation with analytic observables, with expected shift across different phase space regimes, indicating that a trained neural network indeed learns some aspects of jet-substructure moments. Our open-source implementation enables reproducible explainability studies for graph-based jet taggers.

---

## Summary

I worked on developing GNN-based jet-tagging classifiers and combined them with explainable AI tools such as GNNExplainer and Shapley values to examine how the model makes its decisions. This work showed that high-performing models do not need to remain black boxes, and that their predictions can stay physically consistent while revealing the jet substructure features they learn.
