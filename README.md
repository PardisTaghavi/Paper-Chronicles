# Paper Chronicles

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repo is a personal record of the research papers I've read, including a brief summary, personal comments, tags, and more.

---

## Overview

- **Purpose**:  
  Keep track of academic papers, their key takeaways, personal commentary, and quick reference links.
  
---

## Daily (for fun) Papers

| **Title / Link** | **Summary** | **Comments** | **Tags** | 
|------------------|-------------|--------------|----------|
|[Contrastive Test-Time Adaptation](https://arxiv.org/pdf/2204.10377) |Paper introduces a method for test-time adaptation, combining self-supervised contrastive learning with denoised pseudo-labeling. They refine pseudo-labels via neighborhood voting in the target feature space, improving robustness.| TBA | *TTT* | 
|[Enhancing Test Time Adaptation with Few-shot Guidance” ](https://arxiv.org/pdf/2409.01341) |introduces Few-Shot Test Time Adaptation (FS-TTA), that combines a small labeled support set with test-time adaptation to improve model performance under domain shifts.| TBA | *TTT* | 
|[Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](https://arxiv.org/pdf/1909.13231) |Paper coined Test-Time Training term for adapting a model during inference using self-supervised tasks (like rotation prediction) to improve robustness to distribution shifts.| TBA |*TTT*, *Object Detection* | 
|[TTT-KD: Test-Time Training with Knowledge Distillation for 3D Segmentation](https://arxiv.org/pdf/2403.11691) |Introduces a method for 3D semantic segmentation. It adapts to domain shifts during test time by leveraging 2D foundation models, achieving SOTA results on out-of-distribution data!| TBA | *TTT*, *KD* | 
|[Bridging the Domain Gap: Self-Supervised 3D Scene Understanding with Foundation Models](https://arxiv.org/pdf/2305.08776) |Paper combines 2D semantic masks, captions, and 3D point clouds to improve 3D scene understanding and 3D scene reconstruction. It outperforms SOTA in detection & segmentation.| TBA | *3D scene reconstruction*| 
|[ Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces](https://arxiv.org/pdf/2412.14171) |A new benchmark probes MLLMs' spatial reasoning from videos. While linguistic prompts fall short, cognitive maps significantly enhance their understanding.| TBA |*MLLMs*, *Spatial Resoning*  | 
|[Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/pdf/2401.06209) |Paper exposes flaws in MLLMs like GPT-4V in basic visual reasoning. It introduces a 'Mixture of Features' approach to address  systemic gaps but shows limited gain, highlighting the need for better visual encoders.| TBA | *MLLMs*, *LLMs*, *CV*|
|[EMMA: End-to-End Multimodal Model for Autonomous Driving](https://arxiv.org/pdf/2410.23262) |Introduces a multimodal approach for AVs, mapping raw camera inputs, navigation commands, and ego history to planning trajectories, 3D objects, and road graphs—all represented in a unified language space.| TBA | *MLLMs*, *AV* | 
| [Revisiting Few-Shot Object Detection with Vision-Language Models](arxiv.org/pdf/2312.14494) |VLMs like #GroundingDINO outperform traditional FSOD but face challenges with open-world inconsistencies. paper introduces a multi-modal setup aligning VLMs to target tasks. | TBA | *VLMs*, *FS* | 
| [Probing 3D Awareness in Visual Foundation Models]( http://arxiv.org/pdf/2404.08636) |Study reveals how vision models with different supervision like DINOv2, CLIP, and StableDiffusion can comprehend 3D information, from depth estimation to multiview consistency. | TBA | *CV* | 
| [ViLLa: Video Reasoning Segmentation with Large Language Model ]( https://arxiv.org/pdf/2407.14500) | A video reasoning segmentation, merging LLMs' textual reasoning with visual tasks. A new benchmark & model handle complex user queries by segmenting video frames. | TBA | *Video Reasoning* | 
| [UniMatch V2: Pushing Semi-Supervised Semantic Segmentation](https://arxiv.org/pdf/2410.10777) | Paper leverages ViT-based DINOv2 encoders for superior performance and reduced training costs of SSS frameworks.| TBA | *KD*, *Semantic Seg* | 
| [CIFD: Controlled Information Flow for Efficient Knowledge Distillation](https://t.co/y7VklcdaBi) | A KD framework replacing Teacher Assistants with Rate-Distortion Modules. They show SOTA results on ImageNet and CLIP models. | TBA | *KD* | 
| [SKD: BRIDGING THE TEACHER-STUDENT GAP THROUGH INTERLEAVED SAMPLING](https://t.co/Zueg5svQ7I) | SKD introduces interleaved sampling between teacher models (e.g.Gemma-7B, Qwen-7B) and student models (e.g.Gemma-2B, Qwen-0.5B) to boost student model performance.” | TBA | *KD* | 
| [VeXKD: A Unified Framework for Cross-Modal Fusion and Knowledge Distillation](https://t.co/mQ5TVi28PY) | A 3D perception framework integrating fusion and distillation to transfer multi-modal insights into single-modal models | TBA | *KD* | 
| [A Simple Framework for Open-Vocabulary Segmentation and Detection](https://arxiv.org/pdf/2303.08131v3) | Brief summary: introduces a unified framework for open-vocabulary segmentation and #detection with focus on task and data discrepancies.| TBA | *CV* |



---

## Contributing

- **Pull Requests**: Submit a PR if you have a paper to add or want to improve existing summaries.  
- **Issues**: Use issues to propose changes, discuss papers in depth, or recommend new features.

