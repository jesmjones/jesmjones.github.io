---
layout: post
title: Unsupervised behavioral classification
description: utilizing tools to unbiasly score behvaioral states
---

Sample implementation of the MotionMapper behavioral analysis methods initially described in the paper “Mapping the stereotyped behaviour of freely-moving fruit flies” by Berman, GJ, Choi, DM, Bialek, W, and Shaevitz, JW, J. Royal Society Interface, 99, 20140672 (2014).

The original MotionMapper software works on videos (not poses) and uses image analysis and multivariate statistical methods (such as PCA, wavelets, and t-SNE). It has been used to find stereotyped behaviors in flies, mice, and other species. This implementation has been modified to work of 3D joint kinematics instead vis python.

In this implementation, when stimulating nociceptors on the fruit flies abdomen, MotionMapper reveals 14 different behavioral states, 4 of which *perhaps* are known
- Region 11 is the ‘abdominal lifting’ state, and/or pausing that happens immediately at the onset of activation.
- Region 13 is the ‘air legs’ state, or jumping that subsequential happens after 
- Region 14 is the period after landing
- Regions 4/5 are walking states

Forked repo [here](https://github.com/jesmjones/motionmapperpy){:target="_blank"}.
![data_07192022 001](https://github.com/user-attachments/assets/ca608ea3-7929-4b6c-9f69-3b70d42e4c4b)
![data_07192022 004](https://github.com/user-attachments/assets/3222af15-1fa3-4baa-acf6-cae6af3d7a36)
![data_07192022 005](https://github.com/user-attachments/assets/688debcb-3009-4c53-b179-39383e484771)

  
![data_07192022_gif](https://github.com/user-attachments/assets/8ed719dc-68b0-4b35-ac98-3c24d217d70b)

- 
Next steps: 
- The unknown states may be worth exploring —> plot kinematics in each state
- Comparison to UMAP
- Control + Silencing experiments



