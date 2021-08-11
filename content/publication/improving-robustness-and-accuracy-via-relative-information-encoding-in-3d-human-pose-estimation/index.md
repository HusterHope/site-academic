---
title: Improving Robustness and Accuracy via Relative Information Encoding in 3D
  Human Pose Estimation
publication_types:
  - "1"
authors:
  - Wenkang Shan;Haopeng Lu;Shanshe Wang;Xinfeng Zhang;Wen Gao;
abstract: Most of the existing 3D human pose estimation approaches mainly focus
  on predicting 3D positional relationships between the root joint and other
  human joints (local motion) instead of the overall trajectory of the human
  body (global motion). Despite the great progress achieved by these approaches,
  they are not robust to global motion, and lack the ability to accurately
  predict local motion with a small movement range. To alleviate these two
  problems, we propose a relative information encoding method that yields
  positional and temporal enhanced representations. Firstly, we encode
  positional in- formation by utilizing relative coordinates of 2D poses to
  enhance the consistency between the input and output distribution. The same
  posture with different absolute 2D positions can be mapped to a common
  representation. It is beneficial to resist the interfer- ence of global motion
  on the prediction results. Second, we encode temporal information by
  establishing the connection between the current pose and other poses of the
  same person within a period of time. More attention will be paid to the
  movement changes before and after the current pose, resulting in better
  prediction performance on local motion with a small movement range. The
  ablation studies validate the effectiveness of the proposed relative
  information encoding method. Besides, we introduce a multi-stage optimization
  method to the whole framework to further exploit the positional and temporal
  enhanced representations. Our method outperforms state-of-the-art methods on
  two public datasets. Code is available at
  https://github.com/paTRICK-swk/Pose3D-RIE.
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: A relative information encoding method that yields positional and
  temporal enhanced representations.
date: 2021-08-04T04:00:00.000Z
---
