---
layout: page
title: Yang Zhao
subtitle: PhD Student, Xi'an Jiaotong University
---

<img src="assets/img/zhao_yang.jpeg" width="180" align="left"
     style="margin-right: 24px; border-radius: 50%; box-shadow: 0 0 6px rgba(0,0,0,0.25);" />

<span style="font-size: 1.35em; font-weight: 700; color:#e74c3c;">Zhao Yang (杨昭)</span>

<div style="display:flex; gap:14px; align-items:center; margin:10px 0 4px 0;">

  <a href="https://scholar.google.com.hk/citations?user=peTexp4AAAAJ&hl=zh-CN" target="_blank">
    <img src="assets/icons/googlescholar.svg" width="22">
  </a>

  <a href="https://github.com/yangzhaojason" target="_blank">
    <img src="assets/icons/github.svg" width="22">
  </a>

  <a href="https://openreview.net/profile?id=%7EZhao_Yang9" target="_blank">
    <img src="assets/icons/or.svg" width="22">
  </a>

  <a href="https://maimai.cn/contact/share/card?u=kviniwiygqrc&_share_channel=copy_link" target="_blank">
    <img src="assets/icons/mm.svg" width="22">
  </a>

</div>

I am pursuing my PhD in the School of Artificial Intelligence at Xi’an Jiaotong University (XJTU),  
with research affiliations at the **State Key Laboratory of Human-Machine Hybrid Augmented Intelligence**,  
the **National Engineering Research Center for Visual Information and Applications**,  
and the **Institute of Artificial Intelligence and Robotics**.


My research lies at the intersection of <span style="color:#3498db;">world-model-centric embodied AI</span>, <span style="color:#3498db;">autonomous driving</span>, and <span style="color:#3498db;">vision-language-action (VLA)</span> systems.  
I’m particularly interested in how latent world models, long-horizon control, and diffusion-based planning can be combined to make robot policies reliable, temporally consistent, and deployable on real platforms.

Previously, I worked on world-model and perception systems at Baidu Apollo (ADFM), Alibaba DAMO Academy, and Huawei Noah’s Ark Lab, and I am now <strong>founding an embodied-intelligence startup</strong>, Cytoderm Intelligent Technology.

<br clear="both" />

---

## Research Overview

My long-term goal is to build <strong>world-model-first autonomous robotics</strong> capable of robust long-horizon reasoning, dexterous manipulation, and real-world deployment.

Methodologically, my work spans:

- **World Models & Generative Planning**  
  Latent 3D / video world models, diffusion-based planners, and chunked action policies for long-horizon control in manipulation and driving.

- **Vision-Language-Action (VLA) for Robotics**  
  World-model-centric VLA architectures for generalizable robotic behavior, including dexterous grasping and manipulation tasks with action chunking, seam-aware execution, and RL fine-tuning over large-scale, unstructured robotic data.

- **Autonomous Driving & 3D Perception**  
  Semi-supervised BEV 3D detection, panoramic surround-view sensing, uncertainty-aware localization, and HD map construction for embodied navigation.

On the application side, my work has been validated on large-scale robotic manipulation benchmarks such as **CALVIN**, **LIBERO**, and real-world robotic platforms, as well as autonomous-driving datasets including **nuScenes**, **KITTI-360**, and **Waymo**.

---

## Career & Education History

| Role                               | Institution / Company                                                                 | Period        |
|------------------------------------|----------------------------------------------------------------------------------------|---------------|
| **Chief Algorithm Researcher**     | Cytoderm Intelligent Technology (Robotics & Embodied AI)                              | 2025 – Present |
| Senior Algorithm Engineer          | Baidu · Apollo (Autonomous Driving & World Models)                                | 2023 – 2025    |
| PhD Student                        | Xi’an Jiaotong University（Institute of Artificial Intelligent and Robotics）                                 | 2023 – Present |
| Senior Algorithm Engineer          | Alibaba · DAMO Academy (3D Perception & BEV Representation)                            | 2021 – 2023    |
| Algorithm Engineer                 | Huawei · Noah’s Ark Lab and Cloud (Machine Learning & Computer Vision)                           | 2019 – 2022    |
| MS Student                         | Huazhong University of Science and Technology (HUST)                                    | 2017 – 2019    |

---

## Expertise

- **Embodied AI & Robot Learning** (2025 – Present)  
  World models, VLA policies, diffusion-based planners, chunked and hierarchical control.

- **Autonomous Driving & 3D Perception** (2020 – 2025)  
  BEV 3D detection, surround-view fisheye perception, HD map construction, planning under uncertainty.

- **Computer Vision & Machine Learning** (2013 – 2019)  
  Semi-supervised learning, tensor methods, model compression and distillation.

---

## News
- **2025.12** – Released **Cytoderm·Robotic Arm**, a lightweight robotic manipulation platform designed for embodied AI research and industrial prototyping. More details: <a href="https://www.cytoderm.ai/" target="_blank">https://www.cytoderm.ai/</a>
- **2025.12** – Launched **Cybopal**, a consumer-level embodied-intelligence robot product for everyday interactive and assistive tasks. See product page: <a href="https://cybopal.com/" target="_blank">https://cybopal.com/</a>
- **2025.11** – *ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning* completed and under review at a top venue in robot learning / AI.  
- **2025.10** – *Object-Guided Semi-Supervised BEV 3D Object Detection with 3D Box Refinement* accepted by **IEEE T-ITS**.  
- **2025.09** – Finished large-scale experiments on LIBERO long-horizon manipulation benchmark with world-model-centric VLA agents.  
- **2024.06** – 1st-place solution for **CVPR 2024 Autonomous Driving Grand Challenge – Predictive World Model Track**.  
- **2024.03** – Multiple works on BEV detection, spherical fusion, and map construction accepted to **CVPR / ACM MM**.

---

## Publications

A more complete and up-to-date list is available on <a href="https://scholar.google.com.hk/citations?user=peTexp4AAAAJ" target="_blank">Google Scholar</a>.  
<!-- Here is a structured list of conference and journal papers using the same card-style layout. -->

### Recent works (2025–2024)

<div style="display:flex; flex-direction:column; gap:18px;">

<!-- ChunkFlow -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/chunkflow.jpg" alt="ChunkFlow" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#e67e22; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">Preprint</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Yinan Shi, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>Under review, 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      VLA policy with chunked actions, overlap blending, and continuity-constrained RL to suppress boundary jitter in long-horizon control.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>] [<a href="#">Project</a>]
    </div>
  </div>
</div>

<!-- DriVerse -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/DriVerse.jpg" alt="DriVerse" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#3498db; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">ACM MM 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      DriVerse: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment
    </div>
    <div style="font-size:0.9em; color:#999;">Xiaofan Li, Chenming Wu, Zhao Yang*, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>ACM Multimedia (ACM MM), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      A navigation-centric world model that conditions on multimodal trajectory prompts and enforces motion-aligned latent dynamics for driving simulation.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>] [<a href="#">Project</a>]
    </div>
  </div>
</div>

<!-- U-ViLAR -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/U-ViLAR.jpg" alt="U-ViLAR" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#9b59b6; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">ICCV 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      U-ViLAR: Uncertainty-Aware Visual Localization for Autonomous Driving via Differentiable Association and Registration
    </div>
    <div style="font-size:0.9em; color:#999;">Xiaofan Li, Zhihao Xu, Chenming Wu, Zhao Yang, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE/CVF International Conference on Computer Vision (ICCV), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Differentiable association and registration with explicit uncertainty modeling for robust large-scale localization in autonomous driving.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- Causal-Planner -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/causal_planner.jpg" alt="Causal-Planner" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#c0392b; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">IROS 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Causal-Planner: Causal Interaction Disentangling with Episodic Memory Gating for Autonomous Planning
    </div>
    <div style="font-size:0.9em; color:#999;">Yibo Yuan, Jianwu Fang, Yang Zhou, Zhao Yang, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Causal interaction modeling and memory-gated policy for interpretable planning in dynamic driving environments.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- Semi-supervised BEV 3D detection -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/bev_semi3d.jpg" alt="Semi-supervised BEV 3D detection" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#27ae60; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">ICRA 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Towards Accurate Semi-Supervised BEV 3D Object Detection with Depth-Aware Refinement and Denoising-Aided Alignment
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Yinan Shi, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE International Conference on Robotics and Automation (ICRA), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Semi-supervised BEV detector with depth-aware refinement, denoising-aided alignment, and robust pseudo-labeling on nuScenes.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- DualDiff+ (Under review) -->
<div style="display:flex; gap:16px; align-items:flex-start; margin-top:18px;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/dual_diff+.jpg" alt="DualDiff+"
         style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#7f8c8d; color:#fff;
                 font-size:0.78em; padding:2px 8px; border-radius:4px;">Under Review</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      DualDiff+: Dual-branch Diffusion for High-fidelity Video Generation with Reward Guidance
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Zezhong Qian, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>Under review, 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Dual-branch diffusion with semantic and motion reward alignment for high-resolution, temporally coherent video synthesis.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>] [<a href="#">Project</a>]
    </div>
  </div>
</div>


<!-- DualDiff -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/dualdiff.jpg" alt="DualDiff" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#16a085; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">ICRA 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      DualDiff: Dual-Branch Diffusion Model for Autonomous Driving with Semantic Fusion
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Haoteng Li, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE International Conference on Robotics and Automation (ICRA), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Dual-branch diffusion model that fuses semantic BEV priors with image features for controllable driving video and occupancy generation.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- T-ITS BEV 3D detection -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/oss3d.jpg" alt="Object-Guided Semi-Supervised BEV 3D Detection" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#e74c3c; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">T-ITS 2025</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Object-Guided Semi-Supervised Bird’s-Eye View 3D Object Detection with 3D Box Refinement
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Yinan Shi, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Semi-supervised BEV framework with object-guided consistency and box refinement, improving label efficiency on large-scale driving datasets.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- EquivFisheye -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/equivfisheye.jpg" alt="EquivFisheye" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#34495e; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">Info Fusion (under review)</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      EquivFisheye: A Spherical Fusion Framework for Panoramic 3D Perception with Surround-View Fisheye Cameras
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Xinglin Pu, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>Submitted to Information Fusion, 2025.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Spherical feature fusion and equivariant pooling for efficient panoramic 3D perception from multi-view fisheye cameras.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- Cadkp -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/cadkp.jpg" alt="Cadkp" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#2980b9; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">CVPR 2024</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Cadkp: Category-aware Knowledge Distillation and Pruning Framework for Lightweight 3D Object Detection
    </div>
    <div style="font-size:0.9em; color:#999;">Haonan Zhang, Longjun Liu, Yuqi Huang, Zhao Yang, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Category-aware distillation and structured pruning to obtain compact yet accurate 3D detectors for autonomous driving.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- RAG-Guided LLMs -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/rag_llm.jpg" alt="RAG-Guided LLMs" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#8e44ad; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">ACM MM 2024</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      RAG-Guided Large Language Models for Visual Spatial Description with Adaptive Hallucination Correction
    </div>
    <div style="font-size:0.9em; color:#999;">Jun Yu, Yunxiang Zhang, Zerui Zhang, Zhao Yang et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>ACM Multimedia (ACM MM), 2024.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Retrieval-augmented LLMs for spatial description, with adaptive hallucination correction in vision-language reasoning.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- Temporal-Informative Adapters (ACM MM 2024) -->
<div style="display:flex; gap:16px; align-items:flex-start; margin-top:10px;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/micro_expression.jpg" alt="VideoMAE adapters"
         style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#d35400; color:#fff;
                 font-size:0.78em; padding:2px 8px; border-radius:4px;">ACM MM 2024</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Temporal-Informative Adapters in VideoMAE V2 and Multi-Scale Feature Fusion for Micro-Expression Spotting-then-Recognize
    </div>
    <div style="font-size:0.9em; color:#999;">Jun Yu,Guopeng Zhao, Yaohui Zhang, Peng He, Zerui Zhang, Zhao Yang, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>ACM Multimedia (ACM MM), 2024.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Temporal adapters and multi-scale fusion for fine-grained micro-expression analysis.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

<!-- IC-Mapper (ACM MM 2024) -->
<div style="display:flex; gap:16px; align-items:flex-start; margin-top:18px;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/ic_mapper.jpg" alt="IC-Mapper"
         style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#d35400; color:#fff;
                 font-size:0.78em; padding:2px 8px; border-radius:4px;">ACM MM 2024</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      IC-Mapper: Instance-Centric Spatio-Temporal Modeling for Online Vectorized Map Construction
    </div>
    <div style="font-size:0.9em; color:#999;">Jiangtong Zhu*, Zhao Yang*, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>ACM Multimedia (ACM MM), 2024.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Instance-centric spatio-temporal modeling for online HD map vectorization from autonomous driving logs.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>


<!-- CVPR 2024 World Model Challenge -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/cvpr2024_worldmodel.jpg" alt="CVPR 2024 Predictive World Model track" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#2ecc71; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">CVPRW 2024 · 1st place</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      The 1st-Place Solution for CVPR 2024 Autonomous Driving Grand Challenge Track on Predictive World Model
    </div>
    <div style="font-size:0.9em; color:#999;">Z. Yang et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>CVPR 2024 Workshop on Autonomous Driving, 2024.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Large-scale world-model solution for multi-step predictive planning in autonomous driving, achieving 1st place in the CVPR 2024 challenge.
    </div>
    <div style="margin-top:6px; font-size:0.9em;">
      [<a href="#">PDF</a>] [<a href="#">Code</a>]
    </div>
  </div>
</div>

</div> <!-- end recent works -->

### Earlier works

<div style="display:flex; flex-direction:column; gap:18px;">

<!-- Malware GAN -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/malware_gan.jpg" alt="Malware GAN" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#34495e; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">Journal 2022</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Flexible Android Malware Detection Model Based on Generative Adversarial Networks with Code Tensor
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Fengyang Deng, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE Transactions on Cyber-Enabled Distributed Computing and Systems, 2022.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      GAN-based code-tensor modeling for robust Android malware detection.
    </div>
  </div>
</div>

<!-- Mean-teacher SSD -->
<!-- <div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/mean_teacher.jpg" alt="Interactive self-training" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#2980b9; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">CVPR 2021</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Interactive Self-Training with Mean Teachers for Semi-Supervised Object Detection
    </div>
    <div style="font-size:0.9em; color:#999;">Z. Yang et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Semi-supervised detector training with interactive self-training and mean-teacher consistency.
    </div>
  </div>
</div> -->

<!-- Secure tensor decomposition -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/secure_tensor.jpg" alt="Secure tensor decomposition" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#16a085; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">T-CSS 2020</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      Secure Tensor Decomposition for Heterogeneous Multimedia Data in Cloud Computing
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang, Cai Fu, et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>IEEE Transactions on Computational Social Systems, 2020.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Privacy-preserving tensor decomposition framework for heterogeneous multimedia data in cloud environments.
    </div>
  </div>
</div>

<!-- WebVision 2020 -->
<div style="display:flex; gap:16px; align-items:flex-start;">
  <div style="position:relative; min-width:210px;">
    <img src="assets/img/papers/webvision.jpg" alt="WebVision 2020" style="width:210px; border-radius:8px; box-shadow:0 0 6px rgba(0,0,0,0.18); object-fit:cover;">
    <span style="position:absolute; top:8px; left:8px; background:#f1c40f; color:#fff; font-size:0.78em; padding:2px 8px; border-radius:4px;">CVPRW 2020 · 1st place</span>
  </div>
  <div>
    <div style="font-weight:600; font-size:1.02em;">
      The 1st-Place Solution for WebVision CVPR 2020 Virtual
    </div>
    <div style="font-size:0.9em; color:#999;">Zhao Yang et al.</div>
    <div style="font-size:0.9em; margin-top:2px;"><em>CVPR 2020 WebVision Challenge Workshop.</em></div>
    <div style="color:#777; font-size:0.9em; margin-top:4px;">
      Large-scale web-vision model with robust training on noisy labels, achieving 1st place in the WebVision 2020 challenge.
    </div>
  </div>
</div>

</div> <!-- end earlier works -->

---

## Service & Misc.

- Reviewer for major conferences and journals in vision and robotics (CVPR, ICCV, ECCV, ACM MM, ICRA, IROS, T-ITS, etc.).  
- Extensive experience with large-scale GPU clusters (A800 / A100), distributed training, and real autonomous driving platforms.  

If you are interested in collaborations on **world models**, **VLA agents**, or **diffusion-based planning**, feel free to contact me by email.
