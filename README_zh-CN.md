# Mini Sora 社区

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Stargazers][stars-shield]][stars-url]
<br />

<!-- PROJECT LOGO -->
<div align="center">

<img src="assets/logo.jpg" width="600"/>
  <div>&nbsp;</div>
  <div align="center">
  </div>
</div>

<div align="center">

[English](README.md) | 简体中文

</div>

<p align="center">
    👋 加入我们的 <a href="https://cdn.vansin.top/minisora.jpg" target="_blank">微信社区</a>
</p>

Mini Sora 开源社区定位为由社区同学自发组织的开源社区（**免费不收取任何费用、不割韭菜**），Mini Sora 计划探索 Sora 的实现路径和后续的发展方向：

- 将定期举办 Sora 的圆桌和社区一起探讨可能性
- 视频生成的现有技术路径探讨

## MiniSora社区复现小组

[**MiniSora复现小组页面**](https://github.com/mini-sora/minisora/tree/main/codes)

### MiniSora的Sora复现目标

1. **GPU-Friendly** : 最好对GPU内存大小和GPU数量要求较低, 比如8卡A100 80G, 8卡A6000 48G, RTX4090 24G之类的算力可以训练和推理
2. **Training-Efficiency** : 不需要训练太久即可有较好的效果
3. **Inference-Efficiency** : 推理生成视频时, 长度和分辨率不要求过高, 如3-10s,480p都是可接受的

### MiniSora-DiT: 基于XTuner复现论文DiT

#### 招募要求

招募MiniSora社区同学使用 `XTuner` 复现 `DiT`, 希望领取任务同学有如下特点：

1. 熟悉 `OpenMMLab MMEngine` 机制
2. 熟悉 `DiT`

#### 背景

1. `DiT` 作者和 `Sora` 作者为同一个
2. `XTuner` 现有能够高效训练 `1000K` 序列长度的核心技术

#### 支持

1. 算力提供 2*A100
2. [**XTuner**](https://github.com/internLM/xtuner) 核心开发者 [P佬@pppppM](https://github.com/pppppM) 会大力支持~

## 最近更新

- [**Stable Diffusion 3**: MM-DiT: Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://stability.ai/news/stable-diffusion-3-research-paper)

## 近期圆桌讨论

### Stable Diffusion 3 论文(MM-DiT)解读

**主讲**：MMagic 核心贡献者

**在线直播时间**：03/12 20:00

**直播看点**：MMagic 核心贡献者为我们领读 Stable Diffusion 3 论文，介绍 Stable Diffusion 3 的架构细节和设计思路。

请使用微信扫码预约视频号直播:

<div align="center">
<img src="assets/SD3论文领读.png" width="100"/>

  <div>&nbsp;</div>
  <div align="center">
  </div>
</div>


[**Sora夜谈之Video Diffusion 综述**](https://github.com/mini-sora/minisora/blob/main/notes/README.md)

**知乎Notes**: [A Survey on Generative Diffusion Model 生成扩散模型综述](https://zhuanlan.zhihu.com/p/684795460)

## 论文共读计划

- [**Sora**: Creating video from text](https://openai.com/sora)
- **Sora技术报告**: [Video generation models as world simulators](https://openai.com/research/video-generation-models-as-world-simulators)
  - [飞书·翻译+精读](https://aibee.feishu.cn/docx/L3JQdoWmLo7gUQxuHJYcglWInwh)
  - [微信公众号·OpenAI Sora视频生成模型技术报告中英全文](https://mp.weixin.qq.com/s?__biz=MzIwOTA1MDAyNA%3D%3D&mid=2649996785&idx=1&sn=2409190221c7f2aaf8ba4f2c1215f6ac)
- **Latte**: [Latte: Latent Diffusion Transformer for Video Generation](https://maxin-cn.github.io/latte_project/)  
  - [Latte论文精读翻译](./notes/latte%E8%AE%BA%E6%96%87%E7%B2%BE%E8%AF%BB%E7%BF%BB%E8%AF%91.pdf)
  - [Latte论文解读](./notes/Latte.md)
- **DiT**: [Scalable Diffusion Models with Transformers](https://arxiv.org/abs/2212.09748)
- **Stable Cascade (ICLR 24 Paper)**: [Würstchen: An efficient architecture for large-scale text-to-image diffusion models](https://openreview.net/forum?id=gU58d5QeGv)

- 更新中...

### 论文共读发表者募集

- [**DiT** (ICCV 23 Paper)](https://github.com/orgs/mini-sora/discussions/39)
- [**Stable Cascade** (ICLR 24 Paper)](https://github.com/orgs/mini-sora/discussions/145)

## 相关工作

| <h3>Diffusion Model</h3> |  |
| :------------- | :------------- |
| **论文**  | **链接** |
| 1) **Guided-Diffusion**: Diffusion Models Beat GANs on Image Synthesis | [**NeurIPS 21 Paper**](https://arxiv.org/abs/2105.05233), [Github](https://github.com/openai/guided-diffusion)|
| 2) **Latent Diffusion**: High-Resolution Image Synthesis with Latent Diffusion Models | [**CVPR 22 Paper**](https://arxiv.org/abs/2112.10752), [Github](https://github.com/CompVis/latent-diffusion) |
| 3) **EDM**: Elucidating the Design Space of Diffusion-Based Generative Models | [**NeurIPS 22 Paper**](https://arxiv.org/abs/2206.00364), [Github](https://github.com/NVlabs/edm) |
| 4) **DDPM**: Denoising Diffusion Probabilistic Models | [**NeurIPS 20 Paper**](https://arxiv.org/abs/2006.11239), [Github](https://github.com/hojonathanho/diffusion) |
| 5) **DDIM**: Denoising Diffusion Implicit Models | [**ICLR 21 Paper**](https://arxiv.org/abs/2010.02502), [Github](https://github.com/ermongroup/ddim) |
| 6) **Score-Based Diffusion**: Score-Based Generative Modeling through Stochastic Differential Equations | [**ICLR 21 Paper**](https://arxiv.org/abs/2011.13456), [Github](https://github.com/yang-song/score_sde), [Blog](https://yang-song.net/blog/2021/score) |
| 7) **Stable Cascade**: Würstchen: An efficient architecture for large-scale text-to-image diffusion models | [**ICLR 24 Paper**](https://openreview.net/forum?id=gU58d5QeGv), [Github](https://github.com/Stability-AI/StableCascade), [Blog](https://stability.ai/news/introducing-stable-cascade) |
| 8) Diffusion Models in Vision: A Survey| [**TPAMI 23 Paper**](https://arxiv.org/abs/2011.13456), [Github](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)|
| <h3>Diffusion Transformer</h3> | |
| **论文**  | **链接** |
| 1) **UViT**: All are Worth Words: A ViT Backbone for Diffusion Models | [**CVPR 23 Paper**](https://arxiv.org/abs/2209.12152), [Github](https://github.com/baofff/U-ViT), [ModelScope](https://modelscope.cn/models?name=UVit&page=1) |
| 2) **DiT**: Scalable Diffusion Models with Transformers | [**ICCV 23 Paper**](https://arxiv.org/abs/2212.09748), [Github](https://github.com/facebookresearch/DiT),  [ModelScope](https://modelscope.cn/models?name=Dit&page=1)|
| 3) **SiT**: Exploring Flow and Diffusion-based Generative Models with Scalable Interpolant Transformers | [**Paper**](https://arxiv.org/abs/2401.08740), [Github](https://github.com/willisma/SiT), [ModelScope](https://modelscope.cn/models/AI-ModelScope/SiT-XL-2-256/summary)|
| 4) **FiT**: Flexible Vision Transformer for Diffusion Model | [**Paper**](https://arxiv.org/abs/2402.12376), [Github](https://github.com/whlzy/FiT) |
| 5) **k-diffusion**: Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers | [**Paper**](https://arxiv.org/pdf/2401.11605v1.pdf), [Github](https://github.com/crowsonkb/k-diffusion) |
| 6) **OpenDiT**: An Easy, Fast and Memory-Efficient System for DiT Training and Inference | [Github](https://github.com/NUS-HPC-AI-Lab/OpenDiT) |
| 7) **Large-DiT**: Large Diffusion Transformer | [Github](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/Large-DiT) |
| 8) **VisionLLaMA**: A Unified LLaMA Interface for Vision Tasks | [**Paper**](https://arxiv.org/abs/2403.00522), [Github](https://github.com/Meituan-AutoML/VisionLLaMA) |
| 9) **Stable Diffusion 3**: MM-DiT: Scaling Rectified Flow Transformers for High-Resolution Image Synthesis | [**Paper**](https://stabilityai-public-packages.s3.us-west-2.amazonaws.com/Stable+Diffusion+3+Paper.pdf), [Blog](https://stability.ai/news/stable-diffusion-3-research-paper) |
| <h3>Baseline Video Generation Models</h3> | |
| **论文**  | **链接** |
| 1) **ViViT**: A Video Vision Transformer | [**ICCV 21 Paper**](https://arxiv.org/pdf/2103.15691v2.pdf), [Github](https://github.com/google-research/scenic) |
| 2) **VideoLDM**: Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models | [**CVPR 23 Paper**](https://arxiv.org/abs/2304.08818) |
| 3) **LVDM**: Latent Video Diffusion Models for High-Fidelity Long Video Generation | [**Paper**](https://arxiv.org/abs/2211.13221), [Github](https://github.com/YingqingHe/LVDM) |
| 4) **LFDM**: Conditional Image-to-Video Generation with Latent Flow Diffusion Models | [**CVPR 23 Paper**](https://arxiv.org/abs/2303.13744), [Github](https://github.com/nihaomiao/CVPR23_LFDM) |
| 5) **MotionDirector**: Motion Customization of Text-to-Video Diffusion Models | [**Paper**](https://arxiv.org/abs/2310.08465), [Github](https://github.com/showlab/MotionDirector) |
| 6) **TGAN-ODE**: Latent Neural Differential Equations for Video Generation | [**Paper**](https://arxiv.org/pdf/2011.03864v3.pdf), [Github](https://github.com/Zasder3/Latent-Neural-Differential-Equations-for-Video-Generation) |
| 7) **Text2Video-Zero**: Text-to-Image Diffusion Models are Zero-Shot Video Generators | [**Paper**](https://arxiv.org/abs/2303.13439), [Github](https://github.com/Picsart-AI-Research/Text2Video-Zero) |
| 8) **VideoCrafter1**: Open Diffusion Models for High-Quality Video Generation | [**Paper**](https://arxiv.org/abs/2310.19512), [Github](https://github.com/AILab-CVC/VideoCrafter) |
| 9) **VideoCrafter2**: Overcoming Data Limitations for High-Quality Video Diffusion Models | [**Paper**](https://arxiv.org/abs/2401.09047), [Github](https://github.com/AILab-CVC/VideoCrafter) |
| <h3>Video Generation</h3> | |
| **论文**  | **链接** |
| 1) **Animatediff**: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning | [**ICLR 24 Paper**](https://arxiv.org/abs/2307.04725), [Github](https://github.com/guoyww/animatediff/), [ModelScope](https://modelscope.cn/models?name=Animatediff&page=1) |
| 2) **I2VGen-XL**: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models | [**Paper**](https://arxiv.org/abs/2311.04145), [Github](https://github.com/ali-vilab/i2vgen-xl),  [ModelScope](https://modelscope.cn/models/iic/i2vgen-xl/summary)|
| 3) **Imagen Video**: High Definition Video Generation with Diffusion Models | [**Paper**](https://arxiv.org/abs/2210.02303) |
| 4) **MoCoGAN**: Decomposing Motion and Content for Video Generation | [**CVPR 18 Paper**](https://arxiv.org/abs/1707.04993) |
| 5) Adversarial Video Generation on Complex Datasets | [**Paper**](https://arxiv.org/abs/1907.06571) |
| 6) **W.A.L.T**: Photorealistic Video Generation with Diffusion Models | [**Paper**](https://arxiv.org/abs/2312.06662) [Project](https://walt-video-diffusion.github.io/)|
| 7) **VideoGPT**: Video Generation using VQ-VAE and Transformers | [**Paper**](https://arxiv.org/abs/2104.10157), [Github](https://github.com/wilson1yan/VideoGPT) |
| 8) Video Diffusion Models | [**Paper**](https://arxiv.org/abs/2204.03458), [Github](https://github.com/lucidrains/video-diffusion-pytorch), [Project](https://video-diffusion.github.io/)|
| 9) **MCVD**: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation | [**NeurIPS 22 Paper**](https://arxiv.org/abs/2205.09853), [Github](https://github.com/voletiv/mcvd-pytorch), [Project](https://mask-cond-video-diffusion.github.io/), [Blog](https://ajolicoeur.ca/2022/05/22/masked-conditional-video-diffusion/) |
| 10) **VideoPoet**: A Large Language Model for Zero-Shot Video Generation | [**Paper**](https://arxiv.org/abs/2312.14125) |
| 11) **MAGVIT**: Masked Generative Video Transformer | [**CVPR 23 Paper**](https://arxiv.org/abs/2212.05199), [Github](https://github.com/google-research/magvit), [Project](https://magvit.cs.cmu.edu/), [Colab](https://github.com/google-research/magvit/blob/main) |
| 12) **EMO**: Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions | [**Paper**](https://arxiv.org/abs/2402.17485), [Github](https://github.com/HumanAIGC/EMO), [Project](https://humanaigc.github.io/emote-portrait-alive/) |
| 13) **SimDA**: Simple Diffusion Adapter for Efficient Video Generation | [**Paper**](https://arxiv.org/pdf/2308.09710.pdf), [Github](https://github.com/ChenHsing/SimDA), [Project](https://chenhsing.github.io/SimDA/) |
| 14) **StableVideo**: Text-driven Consistency-aware Diffusion Video Editing | [**ICCV 23 Paper**](https://arxiv.org/abs/2308.09592), [Github](https://github.com/rese1f/StableVideo), [Project](https://rese1f.github.io/StableVideo/) |
| 15) **SVD**: Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets| [**Paper**](https://static1.squarespace.com/static/6213c340453c3f502425776e/t/655ce779b9d47d342a93c890/1700587395994/stable_video_diffusion.pdf), [Github](https://github.com/Stability-AI/generative-models)|
| 16) **ADD**: Adversarial Diffusion Distillation| [**Paper**](https://static1.squarespace.com/static/6213c340453c3f502425776e/t/65663480a92fba51d0e1023f/1701197769659/adversarial_diffusion_distillation.pdf), [Github](https://github.com/Stability-AI/generative-models) |
| 17) **GenTron:** Diffusion Transformers for Image and Video Generation | [**CVPR 24 Paper**](http://arxiv.org/abs/2312.04557), [Project](https://www.shoufachen.com/gentron_website/)|
| <h3>Patches Project<h3> | |
| **论文** | **链接** |
| 1) Interactive Video Stylization Using Few-Shot Patch-Based Training | [**Paper**](https://ondrejtexler.github.io/res/Texler20-SIG_patch-based_training_main.pdf),[Github](https://github.com/OndrejTexler/Few-Shot-Patch-Based-Training) |
| 2)  **Zoom-VQA**: Patches, Frames and Clips Integration for Video Quality Assessment | [**Paper**](https://arxiv.org/pdf/2304.06440.pdf),[Github](https://github.com/k-zha14/Zoom-VQA) |
| 3) **FlexiViT**: One Model for All Patch Sizes | [**Paper**](https://arxiv.org/pdf/2212.08013.pdf),[Github](https://github.com/bwconrad/flexivit.git) |
| 4) **MagViT2**: Language Model Beats Diffusion -- Tokenizer is Key to Visual Generation | [**ICLR 24 Paper**](https://arxiv.org/pdf/2310.05737.pdf),[Github](https://github.com/lucidrains/magvit2-pytorch) |
| 5) **CogVideo**: Large-scale Pretraining for Text-to-Video Generation via Transformers | [**ICLR 23 Paper**](https://arxiv.org/pdf/2205.15868.pdf), [Github](https://github.com/THUDM/CogVideo.git) |
| <h3>Long-context</h3> | |
| **论文**  | **链接** |
| 1) World Model on Million-Length Video And Language With RingAttention | [**Paper**](https://arxiv.org/abs/2402.08268), [Github](https://github.com/LargeWorldModel/LWM) |
| 2) Ring Attention with Blockwise Transformers for Near-Infinite Context | [**Paper**](https://arxiv.org/abs/2310.01889), [Github](https://github.com/lhao499/RingAttention) |
| 3) Extending LLMs' Context Window with 100 Samples | [**Paper**](https://arxiv.org/abs/2401.07004), [Github](https://github.com/GAIR-NLP/Entropy-ABF) |
| 4) Efficient Streaming Language Models with Attention Sinks | [**ICLR 24 Paper**](https://arxiv.org/abs/2309.17453), [Github](https://github.com/mit-han-lab/streaming-llm) |
| 5) The What, Why, and How of Context Length Extension Techniques in Large Language Models – A Detailed Survey | [**Paper**](https://arxiv.org/pdf/2401.07872) |
| 6) **MovieChat**: From Dense Token to Sparse Memory for Long Video Understanding | [**CVPR 24 Paper**](https://arxiv.org/abs/2307.16449), [Github](https://github.com/rese1f/MovieChat), [Project](https://rese1f.github.io/MovieChat/) |
| <h3>Audio Related Resource</h3> | |
| **论文**  | **链接** |
| 1) **Stable Audio**: Fast Timing-Conditioned Latent Audio Diffusion | [Link](https://stability.ai/research/stable-audio-efficient-timing-latent-diffusion)|
| 2) **MM-Diffusion**: Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation | [**CVPR 23 Paper**](http://openaccess.thecvf.com/content/CVPR2023/papers/Ruan_MM-Diffusion_Learning_Multi-Modal_Diffusion_Models_for_Joint_Audio_and_Video_CVPR_2023_paper.pdf), [Github](https://github.com/researchmm/MM-Diffusion) |
| 3) **Pengi**: An Audio Language Model for Audio Tasks        | [**NeurIPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/3a2e5889b4bbef997ddb13b55d5acf77-Paper-Conference.pdf), [Github](https://github.com/microsoft/Pengi) |
| 4) **Vast:** A vision-audio-subtitle-text omni-modality foundation model and dataset | [**NeurlPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/e6b2b48b5ed90d07c305932729927781-Paper-Conference.pdf), [Github](https://github.com/TXH-mercury/VAST) |
| 5) **NaturalSpeech**: End-to-End Text to Speech Synthesis with Human-Level Quality | [**Paper**](https://arxiv.org/pdf/2205.04421v2.pdf), [Github](https://github.com/heatz123/naturalspeech)|
| 6) **NaturalSpeech 2**: Latent Diffusion Models are Natural and Zero-Shot Speech and Singing Synthesizers| [**Paper**](https://arxiv.org/abs/2304.09116), [Github](https://github.com/lucidrains/naturalspeech2-pytorch) |
| 7) **UniAudio**: An Audio Foundation Model Toward Universal Audio Generation| [**Paper**](https://arxiv.org/abs/2310.00704), [Github](https://github.com/uniaudio666/UniAudio) |
| <h3>Consistency</h3> | |
| **论文**  | **链接** |
| 1) Layered Neural Atlases for Consistent Video Editing | [**TOG 21 Paper**](https://arxiv.org/pdf/2109.11418.pdf), [Github](https://github.com/ykasten/layered-neural-atlases), [Project](https://layered-neural-atlases.github.io/), |
| 2) **StableVideo**: Text-driven Consistency-aware Diffusion Video Editing | [**ICCV 23 Paper**](https://arxiv.org/abs/2308.09592), [Github](https://github.com/rese1f/StableVideo), [Project](https://rese1f.github.io/StableVideo/) |
| 3) **CoDeF**: Content Deformation Fields for Temporally Consistent Video Processing | [**Paper**](https://arxiv.org/pdf/2308.07926.pdf), [Github](https://github.com/qiuyu96/CoDeF), [Project](https://qiuyu96.github.io/CoDeF/) |
| 4) Consistency Models | [**ICML 23 Paper**](https://arxiv.org/pdf/2303.01469.pdf), [Github](https://github.com/openai/consistency_models) |
| <h3>Prompt Engineering</h3> | |
| **论文**  | **链接** |
| 1) **RealCompo**: Dynamic Equilibrium between Realism and Compositionality Improves Text-to-Image Diffusion Models | [**Paper**](https://arxiv.org/abs/2402.12908), [Github](https://github.com/YangLing0818/RealCompo), [Project](https://cominclip.github.io/RealCompo_Page/) |
| 2) **Mastering Text-to-Image Diffusion**: Recaptioning, Planning, and Generating with Multimodal LLMs | [**Paper**](https://arxiv.org/abs/2401.11708), [Github](https://github.com/YangLing0818/RPG-DiffusionMaster) |
| 3) **LLM-grounded Diffusion**: Enhancing Prompt Understanding of Text-to-Image Diffusion Models with Large Language Models | [**TMLR 23 Paper**](https://arxiv.org/abs/2305.13655), [Github](https://github.com/TonyLianLong/LLM-groundedDiffusion) |
| 4) **LLM BLUEPRINT**: ENABLING TEXT-TO-IMAGE GEN-ERATION WITH COMPLEX AND DETAILED PROMPTS | [**ICLR 24 Paper**](https://arxiv.org/abs/2310.10640), [Github](https://github.com/hananshafi/llmblueprint) |
| 5) Progressive Text-to-Image Diffusion with Soft Latent Direction | [**Paper**](https://arxiv.org/abs/2309.09466) |
| 6) Self-correcting LLM-controlled Diffusion Models | [**CVPR 24 Paper**](https://arxiv.org/abs/2311.16090), [Github](https://github.com/tsunghan-wu/SLD) |
| 7) **LayoutLLM-T2I**: Eliciting Layout Guidance from LLM for Text-to-Image Generation | [**MM 23 Paper**](https://arxiv.org/abs/2308.05095) |
| 8) **LayoutGPT**: Compositional Visual Planning and Generation with Large Language Models | [**NeurIPS 23 Paper**](https://arxiv.org/abs/2305.15393), [Github](https://github.com/weixi-feng/LayoutGPT) |
| 9) **Gen4Gen**: Generative Data Pipeline for Generative Multi-Concept Composition | [**Paper**](https://arxiv.org/abs/2402.15504), [Github](https://github.com/louisYen/Gen4Gen) |
| 10) **InstructEdit**: Improving Automatic Masks for Diffusion-based Image Editing With User Instructions | [**Paper**](https://arxiv.org/abs/2305.18047), [Github](https://github.com/QianWangX/InstructEdit) |
| 11) Controllable Text-to-Image Generation with GPT-4 | [**Paper**](https://arxiv.org/abs/2305.18583) |
| 12) LLM-grounded Video Diffusion Models | [**ICLR 24 Paper**](https://arxiv.org/abs/2309.17444) |
| 13) **VideoDirectorGPT**: Consistent Multi-scene Video Generation via LLM-Guided Planning | [**Paper**](https://arxiv.org/abs/2309.15091) |
| 14) **FlowZero**: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic Scene Syntax | [**Paper**](https://arxiv.org/abs/2311.15813) |
| 15) **VideoDrafter**: Content-Consistent Multi-Scene Video Generation with LLM | [**Paper**](https://arxiv.org/abs/2401.01256) |
| 16) **Free-Bloom**: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator | [**NeurIPS 23 Paper**](https://arxiv.org/abs/2309.14494) |
| 17) Empowering Dynamics-aware Text-to-Video Diffusion with Large Language Models | [**Paper**](https://arxiv.org/abs/2308.13812) |
| 18) **MotionZero**: Exploiting Motion Priors for Zero-shot Text-to-Video Generation | [**Paper**](https://arxiv.org/abs/2311.16635) |
| 19) **GPT4Motion**: Scripting Physical Motions in Text-to-Video Generation via Blender-Oriented GPT Planning | [**Paper**](https://arxiv.org/abs/2311.12631) |
| <h3>Security</h3> | |
| **论文**  | **链接** |
| 1) **BeaverTails:** Towards Improved Safety Alignment of LLM via a Human-Preference Dataset | [**NeurIPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/4dbb61cb68671edc4ca3712d70083b9f-Paper-Datasets_and_Benchmarks.pdf), [Github](https://github.com/PKU-Alignment/beavertails) |
| 2) **LIMA:** Less Is More for Alignment                      | [**NeurIPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/ac662d74829e4407ce1d126477f4a03a-Paper-Conference.pdf) |
| 3) **Jailbroken:** How Does LLM Safety Training Fail?        | [**NeurIPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/fd6613131889a4b656206c50a8bd7790-Paper-Conference.pdf) |
| 4) **Safe Latent Diffusion:** Mitigating Inappropriate Degeneration in Diffusion Models | [**CVPR 23 Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Schramowski_Safe_Latent_Diffusion_Mitigating_Inappropriate_Degeneration_in_Diffusion_Models_CVPR_2023_paper.pdf) |
| 5) **Stable Bias:** Evaluating Societal Representations in Diffusion Models | [**NeurIPS 23 Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/file/b01153e7112b347d8ed54f317840d8af-Paper-Datasets_and_Benchmarks.pdf) |
| <h3>World Model</h3> | |
| **论文**  | **链接** |
| 1) **NExT-GPT**: Any-to-Any Multimodal LLM | [**Paper**](https://arxiv.org/abs/2309.05519), [Github](https://github.com/NExT-GPT/NExT-GPT) |
|  | |
| <h3>Dataset</h3> | |
| **数据集名称 - 论文**  | **链接** |
| 1) **Panda-70M** - Panda-70M: Captioning 70M Videos with Multiple Cross-Modality Teachers<br><small>`70M Clips, 720P, Downloadable`</small>|[**CVPR 24 Paper**](https://arxiv.org/abs/2402.19479), [Github](https://github.com/snap-research/Panda-70M), [Project](https://snap-research.github.io/Panda-70M/)|
| 2) **InternVid-10M** - InternVid: A Large-scale Video-Text Dataset for Multimodal Understanding and Generation<br><small>`10M Clips, 720P, Downloadable`</small>|[**ArXiv 24 Paper**](https://arxiv.org/abs/2307.06942), [Github](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid)|
| 3) **CelebV-Text** - CelebV-Text: A Large-Scale Facial Text-Video Dataset<br><small>`70K Clips, 720P, Downloadable`</small>|[**CVPR 23 Paper**](https://arxiv.org/abs/2303.14717), [Github](https://github.com/celebv-text/CelebV-Text), [Project](https://celebv-text.github.io/)|
| 4) **HD-VG-130M** - VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-Video Generation<br><small> `130M Clips, 720P, Downloadable`</small>|[**ArXiv 23 Paper**](https://arxiv.org/abs/2305.10874), [Github](https://github.com/daooshee/HD-VG-130M), [Tool](https://github.com/Breakthrough/PySceneDetect)|
| 5) **HD-VILA-100M** - Advancing High-Resolution Video-Language Representation with Large-Scale Video Transcriptions<br><small> `100M Clips, 720P, Downloadable`</small>|[**CVPR 22 Paper**](https://arxiv.org/abs/2111.10337), [Github](https://github.com/microsoft/XPretrain/blob/main/hd-vila-100m/README.md)|
| 6) **VideoCC** - Learning Audio-Video Modalities from Image Captions<br><small>`10.3M Clips, 720P, Downloadable`</small>|[**ECCV 22 Paper**](https://arxiv.org/abs/2204.00679), [Github](https://github.com/google-research-datasets/videoCC-data)|
| 7) **YT-Temporal-180M** - MERLOT: Multimodal Neural Script Knowledge Models<br><small>`180M Clips, 480P, Downloadable`</small>| [**NeurIPS 21 Paper**](https://arxiv.org/abs/2106.02636), [Github](https://github.com/rowanz/merlot), [Project](https://rowanzellers.com/merlot/#data)|
| 8) **HowTo100M** - HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips<br><small>`136M Clips, 240P, Downloadable`</small>| [**ICCV 19 Paper**](https://arxiv.org/abs/1906.03327), [Github](https://github.com/antoine77340/howto100m), [Project](https://www.di.ens.fr/willow/research/howto100m/)|
| 9) **UCF101** - UCF101: A Dataset of 101 Human Actions Classes From Videos in The Wild<br><small>`13K Clips, 240P, Downloadable`</small>| [**CVPR 12 Paper**](https://arxiv.org/abs/1212.0402), [Project](https://www.crcv.ucf.edu/data/UCF101.php)|
| 10) **MSVD** - Collecting Highly Parallel Data for Paraphrase Evaluation<br><small>`122K Clips, 240P, Downloadable`</small> | [**ACL 11 Paper**](https://aclanthology.org/P11-1020.pdf), [Project](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/)|
| <h3>现有高质量资料</h3> | |
| **资料**  | **链接** |
| 1) Datawhale - AI视频生成学习 | [Feishu doc](https://datawhaler.feishu.cn/docx/G4LkdaffWopVbwxT1oHceiv9n0c) |
| 2) A Survey on Generative Diffusion Model | [**TKDE 24 Paper**](https://arxiv.org/pdf/2209.02646.pdf), [Github](https://github.com/chq1155/A-Survey-on-Generative-Diffusion-Model) |
| 3) Awesome-Video-Diffusion-Models: A Survey on Video Diffusion Models | [**Paper**](https://arxiv.org/abs/2310.10647), [Github](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models) |
| 4) Awesome-Text-To-Video：A Survey on Text-to-Video Generation/Synthesis  | [Github](https://github.com/jianzhnie/awesome-text-to-video)|
| 5) video-generation-survey: A reading list of video generation| [Github](https://github.com/yzhang2016/video-generation-survey)|
| 6) Awesome-Video-Diffusion |  [Github](https://github.com/showlab/Awesome-Video-Diffusion) |
| 7) Video Generation Task in Papers With Code |  [Link](https://paperswithcode.com/task/video-generation) |
| 8) Sora: A Review on Background, Technology, Limitations, and Opportunities of Large Vision Models |  [**Paper**](https://arxiv.org/abs/2402.17177), [Github](https://github.com/lichao-sun/SoraReview), [中文翻译](https://mp.weixin.qq.com/s/KsmRg7SyCpRs7Bf3D48D2A)|
| 9) Open-Sora-Plan (PKU-YuanGroup) |  [Github](https://github.com/PKU-YuanGroup/Open-Sora-Plan) |
| 10) State of the Art on Diffusion Models for Visual Computing | [**Paper**](http://arxiv.org/abs/2310.07204) |
| 11) Diffusion Models: A Comprehensive Survey of Methods and Applications | [**CSUR 24 Paper**](https://arxiv.org/abs/2209.00796), [Github](https://github.com/YangLing0818/Diffusion-Models-Papers-Survey-Taxonomy) |
| 12) Generate Impressive Videos with Text Instructions: A Review of OpenAI Sora, Stable Diffusion, Lumiere and Comparable | [**Paper**](https://www.techrxiv.org/users/684880/articles/718900-generate-impressive-videos-with-text-instructions-a-review-of-openai-sora-stable-diffusion-lumiere-and-comparable) |
| 13) On the Design Fundamentals of Diffusion Models: A Survey | [**Paper**](http://arxiv.org/abs/2306.04542) |
| 14) Efficient Diffusion Models for Vision: A Survey | [**Paper**](http://arxiv.org/abs/2210.09292) |
| 15) Text-to-Image Diffusion Models in Generative AI: A Survey | [**Paper**](http://arxiv.org/abs/2303.07909) |
| 16) Awesome-Diffusion-Transformers | [GitHub](https://github.com/ShoufaChen/Awesome-Diffusion-Transformers), [Page](https://www.shoufachen.com/Awesome-Diffusion-Transformers/) |
| 17) Open-Sora (HPC-AI Tech) |  [GitHub](https://github.com/hpcaitech/Open-Sora), [Blog](https://hpc-ai.com/blog/open-sora) |

## Mini Sora 微信社区社区交流群

<div align="center">
<img src="assets/qrcode.png" width="200"/>

  <div>&nbsp;</div>
  <div align="center">
  </div>
</div>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mini-sora/minisora&type=Date)](https://star-history.com/#mini-sora/minisora&Date)

## 如何向Mini Sora 社区贡献

我们非常希望你们能够为 Mini Sora 开源社区做出贡献，并且帮助我们把它做得比现在更好！

具体查看[贡献指南](./.github/CONTRIBUTING_zh-CN.md)

## 社区贡献者

<!-- readme: collaborators,contributors -start -->

<!-- readme: collaborators,contributors -end -->

<a href="https://github.com/mini-sora/minisora/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mini-sora/minisora" />
</a>

[your-project-path]: mini-sora/minisora
[contributors-shield]: https://img.shields.io/github/contributors/mini-sora/minisora.svg?style=flat-square
[contributors-url]: https://github.com/mini-sora/minisora/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/mini-sora/minisora.svg?style=flat-square
[forks-url]: https://github.com/mini-sora/minisora/network/members
[stars-shield]: https://img.shields.io/github/stars/mini-sora/minisora.svg?style=flat-square
[stars-url]: https://github.com/mini-sora/minisora/stargazers
[issues-shield]: https://img.shields.io/github/issues/mini-sora/minisora.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/mini-sora/minisora.svg
[license-shield]: https://img.shields.io/github/license/mini-sora/minisora.svg?style=flat-square
[license-url]: https://github.com/mini-sora/minisora/blob/main/LICENSE
