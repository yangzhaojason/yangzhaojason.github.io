---
layout: page
title: Yang Zhao
subtitle: PhD Student, Xi'an Jiaotong University
---

<img src="assets/img/avatar.jpg" width="180" align="left" style="margin-right: 24px; border-radius: 50%; box-shadow: 0 0 6px rgba(0,0,0,0.25);" />

<!-- About block -->
<span style="font-size: 1.15em; font-weight: 600; color:#e74c3c;">Yang Zhao (赵阳)</span> is a PhD student at the 
<a href="https://sai.xjtu.edu.cn/" target="_blank">School of Artificial Intelligence, Xi'an Jiaotong University</a>, 
advised by <a href="mailto:liulongjun@xjtu.edu.cn" target="_blank">Prof. Longjun Liu</a>.

His research lies at the intersection of 
<span style="color:#3498db;">world-model-centric embodied AI</span>, 
<span style="color:#3498db;">autonomous driving</span>, and 
<span style="color:#3498db;">vision-language-action (VLA)</span> systems.
He is particularly interested in how latent world models, long-horizon control, and diffusion-based planning can be combined
to make robot policies both reliable and deployable.

Previously, he worked as a research engineer on world-model and perception systems at
Baidu Apollo (ADFM), Alibaba DAMO Academy, and Huawei Noah's Ark Lab.

<br clear="both" />

---

## Research Overview

My long-term goal is to build  
<strong>world-model-first autonomous agents</strong> capable of robust long-horizon reasoning and real-world deployment.

Methodologically, my work spans:

- **World Models & Generative Planning**  
  Latent 3D / video world models, diffusion-based planners, and chunked action policies for long-horizon manipulation and driving.

- **Autonomous Driving & 3D Perception**  
  Semi-supervised BEV 3D detection, panoramic surround-view perception, and uncertainty-aware localization.

- **Vision-Language-Action (VLA) Systems**  
  World-model-centric VLA architectures, action chunking, seam-aware execution, and RL fine-tuning over unstructured data.

On the application side, my work has been validated on large-scale benchmarks such as nuScenes, KITTI-360, CALVIN, LIBERO, and real autonomous driving platforms.

---

## Career & Education History

| Role              | Institution / Company                                                                 | Period        |
|-------------------|---------------------------------------------------------------------------------------|---------------|
| Researcher        | Cytoderm Itelligent Technology                                                        | 2025 – Present |
| Researcher        | Autonomous Driving Group, Baidu (Apollo ADFM)                                         | 2023 – 2025    |
| Researcher        | DAMO Academy, Alibaba Group                                                           | 2021 – 2023    |
| PhD Student       | School of Artificial Intelligence, Xi'an Jiaotong University                          | 2023 – Present |
| Researcher        | Noah's Ark Lab, Huawei Technologies                                                   | 2019 – 2022    |
| MS Student        | Information Security, Huazhong University of Science and Technology (HUST)            | 2017 – 2019    |

---

## Expertise

- **Embodied AI & Robot Learning** (2025 – Present)  
  World models, VLA policies, diffusion-based planners, chunked control.

- **Autonomous Driving & 3D Perception** (2020 – Present)  
  BEV 3D detection, surround-view fisheye perception, HD map construction, planning with uncertainty.

- **Computer Vision & Machine Learning** (2013 – 2019)  
  Semi-supervised learning, tensor methods, model compression and distillation.

---

## News

<!-- 近期可以自己按时间补充，这里先给几个模板式例子 -->
- **2025.11** – *ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning* submitted to a top conference on robot learning / AI.
- **2025.10** – *Object-Guided Semi-Supervised BEV 3D Object Detection with 3D Box Refinement* accepted by **IEEE T-ITS**.
- **2025.09** – Completed large-scale experiments on LIBERO long-horizon manipulation benchmark with world-model-centric VLA agents.
- **2024.06** – 1st-place solution for **CVPR 2024 Autonomous Driving Grand Challenge – Predictive World Model Track**.
- **2024.03** – Multiple works on BEV detection, spherical fusion, and map construction accepted to **CVPR / ACM MM**.

---

## Featured Research

<div style="display:flex; flex-direction:column; gap:18px;">

<!-- ChunkFlow card -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <img src="assets/img/chunkflow_thumb.jpg" alt="ChunkFlow thumbnail" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.2); object-fit:cover;">
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning
    </div>
    <div style="color:#777; font-size:0.95em; margin-bottom:4px;">
      Long-horizon manipulation with seam-aware chunked policies, deterministic overlap blending, and continuity-regularized RL fine-tuning.
    </div>
    <div style="font-size:0.9em;">
      <span style="color:#e74c3c;">VLA · Long-horizon control · World models</span>
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#" target="_blank">PDF (coming soon)</a>] &nbsp;
      [<a href="#" target="_blank">Code</a>] &nbsp;
      [<a href="#" target="_blank">Video</a>]
    </div>
  </div>
</div>

<!-- DriVerse card -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <img src="assets/img/driverse_thumb.jpg" alt="DriVerse thumbnail" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.2); object-fit:cover;">
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      DriVerse: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment
    </div>
    <div style="color:#777; font-size:0.95em; margin-bottom:4px;">
      World-model-based simulator for driving with multimodal trajectory prompts and motion-aligned latent dynamics.
    </div>
    <div style="font-size:0.9em;">
      <span style="color:#e67e22;">Autonomous driving · World models · Generative simulation</span>
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#" target="_blank">PDF</a>] &nbsp;
      [<a href="#" target="_blank">Code</a>] &nbsp;
      [<a href="#" target="_blank">Demo video</a>]
    </div>
  </div>
</div>

<!-- DualDiff+ card -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <img src="assets/img/dualdiff_thumb.jpg" alt="DualDiff+ thumbnail" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.2); object-fit:cover;">
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      DualDiff+: Dual-Branch Diffusion for High-Fidelity Video Generation with Reward Guidance
    </div>
    <div style="color:#777; font-size:0.95em; margin-bottom:4px;">
      Dual-branch diffusion with occupancy-aware structure branch and appearance branch, combined with reward-guided sampling for controllable driving video generation.
    </div>
    <div style="font-size:0.9em;">
      <span style="color:#16a085;">Diffusion · Video generation · Reward guidance</span>
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#" target="_blank">PDF</a>] &nbsp;
      [<a href="#" target="_blank">Code</a>] &nbsp;
      [<a href="#" target="_blank">Project page</a>]
    </div>
  </div>
</div>

</div>

<p style="margin-top:10px; font-size:0.9em;">
  (*Thumbnails are placeholders – replace with your own figures or teaser images.*)
</p>

---

## Selected Publications

A more complete and up-to-date list is available on 
<a href="https://scholar.google.com.hk/citations?user=peTexp4AAAAJ" target="_blank">Google Scholar</a>.  
Below is a selection of recent and representative works.

### 2025

- **ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning**  
  <span style="color:#999;">Z. Yang, Y. Shi, M. Yao, W. Xue, Y. Jueluo, L. Liu</span>.  
  *Preprint / under review, 2025.*  
  Long-horizon VLA policy with chunked actions, seam-aware blending, and continuity-constrained RL fine-tuning.

- **DriVerse: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment**  
  *ACM Multimedia (ACM MM), 2025.*  

- **U-ViLAR: Uncertainty-Aware Visual Localization for Autonomous Driving via Differentiable Association and Registration**  
  *IEEE/CVF International Conference on Computer Vision (ICCV), 2025.*

- **Causal-Planner: Causal Interaction Disentangling with Episodic Memory Gating for Autonomous Planning**  
  *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025.*

- **Towards Accurate Semi-Supervised BEV 3D Object Detection with Depth-Aware Refinement and Denoising-Aided Alignment**  
  *IEEE International Conference on Robotics and Automation (ICRA), 2025.*

- **DualDiff: Dual-branch Diffusion Model for Autonomous Driving with Semantic Fusion**  
  *IEEE International Conference on Robotics and Automation (ICRA), 2025.*

- **DualDiff+: Dual-branch Diffusion for High-fidelity Video Generation with Reward Guidance**  
  *arXiv preprint, 2025.*

- **Object-Guided Semi-Supervised Bird’s-Eye View 3D Object Detection with 3D Box Refinement**  
  *IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025.*

- **EquivFisheye: A Spherical Fusion Framework for Panoramic 3D Perception with Surround-View Fisheye Cameras**  
  *Preprint / under review (Information Fusion), 2025.*

### 2024

- **Cadkp: Category-aware Knowledge Distillation and Pruning Framework for Lightweight 3D Object Detection**  
  *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024.*

- **RAG-Guided Large Language Models for Visual Spatial Description with Adaptive Hallucination Correction**  
  *ACM Multimedia (ACM MM), 2024.*

- **Temporal-Informative Adapters in VideoMAE V2 and Multi-Scale Feature Fusion for Micro-Expression Spotting-then-Recognize**  
  *ACM Multimedia (ACM MM), 2024.*

- **IC-Mapper: Instance-Centric Spatio-Temporal Modeling for Online Vectorized Map Construction**  
  *ACM Multimedia (ACM MM), 2024.*

- **The 1st-Place Solution for CVPR 2024 Autonomous Grand Challenge Track on Predictive World Model**  
  *CVPR Workshop / Challenge on Autonomous Driving, 2024.*

### 2022–2020

- **Flexible Android Malware Detection Model Based on Generative Adversarial Networks with Code Tensor**  
  *IEEE Transactions on Cyber-Enabled Distributed Computing and Systems, 2022.*

- **Interactive Self-Training with Mean Teachers for Semi-Supervised Object Detection**  
  *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021.*

- **Secure Tensor Decomposition for Heterogeneous Multimedia Data in Cloud Computing**  
  *IEEE Transactions on Computational Social Systems, 2020.*

- **The 1st-Place Solution for WebVision CVPR 2020 Virtual**  
  *CVPR Workshop on WebVision, 2020.*

---

## Service & Misc.

- Reviewer for major conferences and journals in vision and robotics (CVPR, ICCV, ICRA, ITSC, T-ITS, etc.).  
- Experience with large-scale GPU clusters (A800/A100), distributed training, and real-world autonomous driving platforms.

If you are interested in **collaborations** on world models, VLA agents, or diffusion-based planning, feel free to contact me by email.
