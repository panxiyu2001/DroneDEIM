⚠️ The complete code will be released after acceptance.

# DroneDEIM: Disentangling Dense and Tiny Objects in UAV Imagery via Hierarchical Feature Refinement

This repository contains the LaTeX source code for the paper
**"DroneDEIM: Disentangling Dense and Tiny Objects in UAV Imagery via Hierarchical Feature Refinement".**
It introduces DroneDEIM, a novel detection framework for UAV object detection, addressing extreme density and tiny objects.

## Abstract

Object detection in Unmanned Aerial Vehicle (UAV) imagery is critically challenged by two issues prevalent in remote sensing: extreme object density with frequent occlusions and the predominance of tiny objects. To address these challenges, this paper proposes DroneDEIM, a novel and efficient detection framework. Our method features a hierarchical refinement process, centered on two key innovations. First, we design the Cross-level Iterative FPN (Cil-FPN), a new feature fusion encoder. Within Cil-FPN, a Frequency-Aware SPPF (FA-SPPF) module first enhances the weak, high-frequency signals of tiny objects, which then guide a Multi-branch Competitive Frequency-guided Module (MCFM) to perform adaptive, cross-scale fusion. Second, our Instance-Disentanglement Module (IDM) Decoder Layer utilizes a query-specific channel modulation mechanism to resolve instance ambiguity in dense scenes. Evaluated on challenging UAV benchmarks, including VisDrone2019, CoDrone, and HIT-UAV, DroneDEIM demonstrates state-of-the-art performance. Notably, our lightweight model achieves 46.5% AP50 on the VisDrone2019 dataset with only 7.6M parameters and 22.6 GFLOPs, establishing a new state-of-the-art in the balance between performance and efficiency for UAV object detection.

![DroneDEIM comparison](comparison_ours_final_layout_updated.pdf)

## Contributions
-Propose DroneDEIM, a complete framework that systematically addresses the co-existing challenges of extreme density and tiny objects in UAV imagery.
-Design a novel feature fusion encoder, Cil-FPN, which synergizes a Frequency-Aware SPPF (FA-SPPF) module to amplify the signals of tiny objects and a Multi-branch Competitive Frequency-guided Module (MCFM) to perform adaptive fusion.
-Propose the IDM-Layer, a new decoder building block that effectively disentangles highly overlapping instances by learning query-aware channel attention.
-Achieve new state-of-the-art results on challenging UAV datasets, outperforming existing methods in both accuracy and efficiency.
