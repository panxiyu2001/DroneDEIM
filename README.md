⚠️ The complete code will be released after acceptance.

#

This repository contains the LaTeX source code for the paper
****
It introduces DroneDEIM, a novel detection framework for UAV object detection, addressing extreme density and tiny objects.

## Abstract
![DroneDEIM Architecture](b.png)
![DroneDEIM comparison](a.png)

## Contributions
- Propose DroneDEIM, a complete framework that systematically addresses the co-existing challenges of extreme density and tiny objects in UAV imagery.
- Design a novel feature fusion encoder, Cil-FPN, which synergizes a Frequency-Aware SPPF (FA-SPPF) module to amplify the signals of tiny objects and a Multi-branch Competitive Frequency-guided Module (MCFM) to perform adaptive fusion.
- Propose the IDM-Layer, a new decoder building block that effectively disentangles highly overlapping instances by learning query-aware channel attention.
- Achieve new state-of-the-art results on challenging UAV datasets, outperforming existing methods in both accuracy and efficiency.
