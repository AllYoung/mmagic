<<<<<<< HEAD
<div id="top" align="center">
  <img src="docs/zh_cn/_static/image/mmagic-logo.png" width="500px"/>
  <div>&nbsp;</div>
  <div align="center">
    <font size="10"><b>M</b>ultimodal <b>A</b>dvanced, <b>G</b>enerative, and <b>I</b>ntelligent <b>C</b>reation (MMagic [em'mædʒɪk])</font>
  </div>
=======
<div align="center">
  <img src="docs/zh_cn/_static/resources/mmediting-logo.png" width="500px"/>
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">OpenMMLab 官网</font></b>
    <sup>
      <a href="https://openmmlab.com">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">OpenMMLab 开放平台</font></b>
    <sup>
      <a href="https://platform.openmmlab.com">
        <i><font size="4">TRY IT OUT</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>

[![PyPI](https://badge.fury.io/py/mmagic.svg)](https://pypi.org/project/mmagic/)
[![docs](https://img.shields.io/badge/docs-latest-blue)](https://mmagic.readthedocs.io/zh_CN/latest/)
[![badge](https://github.com/open-mmlab/mmagic/workflows/build/badge.svg)](https://github.com/open-mmlab/mmagic/actions)
[![codecov](https://codecov.io/gh/open-mmlab/mmagic/branch/master/graph/badge.svg)](https://codecov.io/gh/open-mmlab/mmagic)
[![license](https://img.shields.io/github/license/open-mmlab/mmagic.svg)](https://github.com/open-mmlab/mmagic/blob/main/LICENSE)
[![open issues](https://isitmaintained.com/badge/open/open-mmlab/mmagic.svg)](https://github.com/open-mmlab/mmagic/issues)
[![issue resolution](https://isitmaintained.com/badge/resolution/open-mmlab/mmagic.svg)](https://github.com/open-mmlab/mmagic/issues)

[📘使用文档](https://mmagic.readthedocs.io/zh_CN/latest/) |
[🛠️安装教程](https://mmagic.readthedocs.io/zh_CN/latest/get_started/install.html) |
[📊模型库](https://mmagic.readthedocs.io/zh_CN/latest/model_zoo/overview.html) |
[🆕更新记录](https://mmagic.readthedocs.io/zh_CN/latest/changelog.html) |
[🚀进行中的项目](https://github.com/open-mmlab/mmagic/projects) |
[🤔提出问题](https://github.com/open-mmlab/mmagic/issues)

[English](README.md) | 简体中文

</div>

<<<<<<< HEAD
=======
<div align="center">

[English](README.md) | 简体中文

</div>

## Introduction

MMEditing 是基于 PyTorch 的图像&视频编辑开源工具箱。是 [OpenMMLab](https://openmmlab.com/) 项目的成员之一。

目前 MMEditing 支持下列任务：

>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895
<div align="center">
  <a href="https://openmmlab.medium.com/" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218352562-cdded397-b0f3-4ca1-b8dd-a60df8dca75b.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://discord.gg/raweFPmdzG" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218347213-c080267f-cbb6-443e-8532-8e1ed9a58ea9.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://twitter.com/OpenMMLab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346637-d30c8a0f-3eba-4699-8131-512fb06d46db.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://www.youtube.com/openmmlab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346691-ceb2116a-465a-40af-8424-9f30d2348ca9.png" width="3%" alt="" /></a>
</div>

## 🚀 最新进展 <a><img width="35" height="20" src="https://user-images.githubusercontent.com/12782558/212848161-5e783dd6-11e8-4fe0-bbba-39ffb77730be.png"></a>

### 最新的 [**MMagic v1.0.1**](https://github.com/open-mmlab/mmagic/releases/tag/v1.0.1) 版本已经在 \[26/05/2023\] 发布:

- 支持 StableDiffusion tomesd 加速.
- 支持所有 inpainting/matting/image restoration 模型的 inferencer.
- 支持 animated drawings.
- 支持 Style-Based Global Appearance Flow for Virtual Try-On.
- 修复 pip install 时 inferencer 无法使用的问题.

我们正式发布 MMagic v1.0.0 版本，源自 [MMEditing](https://github.com/open-mmlab/mmediting) 和 [MMGeneration](https://github.com/open-mmlab/mmgeneration)。

<<<<<<< HEAD
经过 OpenMMLab 2.0 框架的迭代更新以及与 MMGeneration 的合并，MMEditing 已经成为了一个支持基于 GAN 和 CNN 的底层视觉算法的强大工具。而今天，MMEditing 将更加拥抱生成式 AI（Generative AI），正式更名为 **MMagic**（**M**ultimodal **A**dvanced, **G**enerative, and **I**ntelligent **C**reation），致力于打造更先进、更全面的 AIGC 开源算法库。MMagic 将为广大研究者与 AIGC 爱好者们提供更加快捷灵活的实验支持，助力你的 AIGC 探索之旅。

以下是此次版本发布的重点新功能:
=======
### 主要特性
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895

**1. 新算法**

我们支持了4个新任务以及11个新算法。

- Text2Image / Diffusion
  - ControlNet
  - DreamBooth
  - Stable Diffusion
  - Disco Diffusion
  - GLIDE
  - Guided Diffusion
- 3D-aware Generation
  - EG3D
- Image Restoration
  - NAFNet
  - Restormer
  - SwinIR
- Image Colorization
  - InstColorization

**2. Magic Diffusion Model**

针对 Diffusion Model，我们提供了以下“魔法”

- 支持基于 Stable Diffusion 与 Disco Diffusion 的图像生成.
- 支持 Dreambooth 以及 DreamBooth LoRA 等 Finetune 方法.
- 支持 ControlNet 进行可控性的文本到图像生成.
- 支持 xFormers 加速和优化策略，提高训练与推理效率.
- 支持基于 MultiFrame Render 的视频生成.
- 支持通过 Wrapper 调用 Diffusers 的基础模型以及采样策略.

**3. 框架升级**

<<<<<<< HEAD
通过 OpenMMLab 2.0 框架的 MMEngine 和 MMCV， MMagic 在以下几方面完成升级：

- 重构 DataSample，支持 batch 维度的组合与拆分.
- 重构 DataPreprocessor，并统一各种任务在训练与推理时的数据格式.
- 重构 MultiValLoop 与 MultiTestLoop，同时支持生成类型指标（e.g. FID）与重建类型指标（e.g. SSIM） 的评测，同时支持一次性评测多个数据集
- 支持本地可视化以及使用 tensorboard 或 wandb的可视化.
- 支持 33+ 算法 Pytorch 2.0 加速.

**MMagic** 已经支持了[MMEditing](https://github.com/open-mmlab/mmediting)和[MMGeneration](https://github.com/open-mmlab/mmgeneration)中的全量任务、模型、优化函数和评价指标 ，并基于[MMEngine](https://github.com/open-mmlab/mmengine)统一了各组件接口 😍。
=======
## 最新进展

MMEditing 同时维护 0.x 和 1.x 版本，详情见[分支维护计划](README_zh-CN.md#分支维护计划)

### 💎 稳定版本

最新的 **0.16.1** 版本已经在 24/02/2023 发布：

- 支持新评价指标 FID 和 KID。
- 支持 ResidualBlockNoBN 模块设置 `groups` 参数。
- 修复 RealESRGAN 测试数据集配置。
- 修复 `pixel-unshuffle` 模块动态输入导出 ONNX 的Bug。

如果像了解更多版本更新细节和历史信息，请阅读[更新日志](/docs/zh_cn/changelog.md)。

### 🌟 1.x 预览版本

全新的 [**MMEditing v1.0.0rc6**](https://github.com/open-mmlab/mmediting/releases/tag/v1.0.0rc6) 已经在 24/02/2023 发布:

- 支持[MMGeneration](https://github.com/open-mmlab/mmgeneration)中的全量任务、模型、优化函数和评价指标 😍。
- 基于[MMEngine](https://github.com/open-mmlab/mmengine)统一了各组件接口。
- 重构之后更加灵活 [architecture](https://mmediting.readthedocs.io/en/1.x/1_overview.html)。
- 支持了著名的文本生成图像方法 [Stable Diffusion](https://github.com/open-mmlab/mmediting/tree/1.x/configs/stable_diffusion/README.md)!
- 支持了一个新的文本到图像生成算法 [GLIDE](https://github.com/open-mmlab/mmediting/tree/1.x/projects/glide/configs/README.md)!
- 支持了一个新的文本到图像生成算法 [Disco-Diffusion](https://github.com/open-mmlab/mmediting/tree/1.x/configs/disco_diffusion/README.md)!
- 支持了3D生成算法 [EG3D](https://github.com/open-mmlab/mmediting/tree/1.x/configs/eg3d/README.md)!
- 支持了一个高效的图像复原算法 [Restormer](https://github.com/open-mmlab/mmediting/tree/1.x/configs/restormer/README.md)!
- 支持了基于swin的图像复原算法 [SwinIR](https://github.com/open-mmlab/mmediting/tree/1.x/configs/swinir/README.md)!
- 支持图像上色算法 [Image Colorization](https://github.com/open-mmlab/mmediting/tree/1.x/configs/inst_colorization/README.md).
- 开启了[Projects](https://github.com/open-mmlab/mmediting/tree/1.x/projects/README.md)以便社区用户添加新的项目到MMEditing.
- 支持了 High-level apis and inferencer.
- 支持Inpainting任务的Gradio交互GUI.
- 支持基于patch以及滑动条的图像和视频可视化比较工具.

在[1.x 分支](https://github.com/open-mmlab/mmediting/tree/1.x)中发现更多特性！欢迎提 Issues 和 PRs！
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895

如果想了解更多版本更新细节和历史信息，请阅读[更新日志](docs/zh_cn/changelog.md)。如果想从[旧版本](https://github.com/open-mmlab/mmagic/tree/master) MMEditing 0.x 迁移到新版本 MMagic 1.x，请阅读[迁移文档](docs/zh_cn/migration/overview.md)。

## 📄 目录

- [📖 介绍](#-介绍)
- [🙌 参与贡献](#-参与贡献)
- [🛠️ 安装](#%EF%B8%8F-安装)
- [📊 模型库](#-模型库)
- [🤝 致谢](#-致谢)
- [🖊️ 引用](#%EF%B8%8F-引用)
- [🎫 许可证](#-许可证)
- [🏗️ ️OpenMMLab 的其他项目](#%EF%B8%8F-️openmmlab-的其他项目)

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 📖 介绍

MMagic 是基于 PyTorch 的图像&视频编辑和生成开源工具箱。是 [OpenMMLab](https://openmmlab.com/) 项目的成员之一。

目前 MMagic 支持多种图像和视频的生成/编辑任务。

https://user-images.githubusercontent.com/49083766/233564593-7d3d48ed-e843-4432-b610-35e3d257765c.mp4

主分支代码的最佳实践基于 **Python 3.8+** 和 **PyTorch 1.9+** 。

### ✨ 主要特性

- **SOTA 算法**

  MMagic 提供了处理、编辑、生成图像和视频的 SOTA 算法。

- **强有力且流行的应用**

  MMagic 支持了流行的图像修复、图文生成、3D生成、图像修补、抠图、超分辨率和生成等任务的应用。特别是 MMagic 支持了 Stable Diffusion 的微调和许多激动人心的 diffusion 应用，例如 ControlNet 动画生成。MMagic 也支持了 GANs 的插值，投影，编辑和其他流行的应用。请立即开始你的 AIGC 探索之旅！

- **高效的框架**

  通过 OpenMMLab 2.0 框架的 MMEngine 和 MMCV， MMagic 将编辑框架分解为不同的组件，并且可以通过组合不同的模块轻松地构建自定义的编辑器模型。我们可以像搭建“乐高”一样定义训练流程，提供丰富的组件和策略。在 MMagic 中，你可以使用不同的 APIs 完全控制训练流程。得益于 [MMSeparateDistributedDataParallel](https://github.com/open-mmlab/mmengine/blob/main/mmengine/model/wrappers/seperate_distributed.py), 动态模型结构的分布式训练可以轻松实现。

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 🙌 参与贡献

越来越多社区贡献者的加入使我们的算法库日益发展。最近由社区贡献的项目包括：

- [GLIDE](projects/glide/configs/README.md) 来自 @Taited.
- [Restormer](configs/restormer/README.md) 来自 @AlexZou14.
- [SwinIR](configs/swinir/README.md) 来自 @Zdafeng.

为使向 MMagic 中添加项目更加容易，我们开启了 [Projects](projects/README.md) 。

感谢您为改善 MMagic 所做的所有贡献。请参阅 MMCV 中的 [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/main/CONTRIBUTING_zh-CN.md) 和 MMEngine 中的 [CONTRIBUTING.md](https://github.com/open-mmlab/mmengine/blob/main/CONTRIBUTING_zh-CN.md) 以获取贡献指南。

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 🛠️ 安装

MMagic 依赖 [PyTorch](https://pytorch.org/)，[MMEngine](https://github.com/open-mmlab/mmengine) 和 [MMCV](https://github.com/open-mmlab/mmcv)，以下是安装的简要步骤。

**步骤 1.**
依照[官方教程](https://pytorch.org/get-started/locally/)安装 PyTorch 。

**步骤 2.**
使用 [MIM](https://github.com/open-mmlab/mim) 安装 MMCV，MMEngine 和 MMagic 。

```
pip3 install openmim
mim install 'mmcv>=2.0.0'
mim install 'mmengine'
mim install 'mmagic'
```

**步骤 3.**
验证 MMagic 安装成功。

```shell
cd ~
python -c "import mmagic; print(mmagic.__version__)"
# Example output: 1.0.0
```

**开始使用**

成功安装 MMagic 后，你可以很容易地上手使用 MMagic！仅需几行代码，你就可以使用 MMagic 完成文本生成图像！

```python
from mmagic.apis import MMagicInferencer
sd_inferencer = MMagicInferencer(model_name='stable_diffusion')
text_prompts = 'A panda is having dinner at KFC'
result_out_dir = 'output/sd_res.png'
sd_inferencer.infer(text=text_prompts, result_out_dir=result_out_dir)
```

请参考[快速运行](docs/zh_cn/get_started/quick_run.md)和[推理演示](docs/zh_cn/user_guides/inference.md)获取 MMagic 的基本用法。

**从源码安装 MMagic**

使用以下命令从源码安装 MMagic，你可以选择不使用已发布的稳定版本，而在最新开发的版本上进行实验。

```
git clone https://github.com/open-mmlab/mmagic.git
cd mmagic
pip3 install -e .
```

更详细的安装指南请参考 [安装指南](docs/zh_cn/get_started/install.md) 。

<p align="right"><a href="#top">🔝Back to top</a></p>

## 📊 模型库

<div align="center">
  <b>支持的算法</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Conditional GANs</b>
      </td>
      <td>
        <b>Unconditional GANs</b>
      </td>
      <td>
        <b>Image Restoration</b>
      </td>
      <td>
        <b>Image Super-Resolution</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <ul>
            <li><a href="configs/sngan_proj/README.md">SNGAN/Projection GAN (ICLR'2018)</a></li>
            <li><a href="configs/sagan/README.md">SAGAN (ICML'2019)</a></li>
            <li><a href="configs/biggan/README.md">BIGGAN/BIGGAN-DEEP (ICLR'2018)</a></li>
      </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/dcgan/README.md">DCGAN (ICLR'2016)</a></li>
          <li><a href="configs/wgan-gp/README.md">WGAN-GP (NeurIPS'2017)</a></li>
          <li><a href="configs/lsgan/README.md">LSGAN (ICCV'2017)</a></li>
          <li><a href="configs/ggan/README.md">GGAN (ArXiv'2017)</a></li>
          <li><a href="configs/pggan/README.md">PGGAN (ICLR'2018)</a></li>
          <li><a href="configs/singan/README.md">SinGAN (ICCV'2019)</a></li>
          <li><a href="configs/styleganv1/README.md">StyleGANV1 (CVPR'2019)</a></li>
          <li><a href="configs/styleganv2/README.md">StyleGANV2 (CVPR'2019)</a></li>
          <li><a href="configs/styleganv3/README.md">StyleGANV3 (NeurIPS'2021)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/swinir/README.md">SwinIR (ICCVW'2021)</a></li>
          <li><a href="configs/nafnet/README.md">NAFNet (ECCV'2022)</a></li>
          <li><a href="configs/restormer/README.md">Restormer (CVPR'2022)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/srcnn/README.md">SRCNN (TPAMI'2015)</a></li>
          <li><a href="configs/srgan_resnet/README.md">SRResNet&SRGAN (CVPR'2016)</a></li>
          <li><a href="configs/edsr/README.md">EDSR (CVPR'2017)</a></li>
          <li><a href="configs/esrgan/README.md">ESRGAN (ECCV'2018)</a></li>
          <li><a href="configs/rdn/README.md">RDN (CVPR'2018)</a></li>
          <li><a href="configs/dic/README.md">DIC (CVPR'2020)</a></li>
          <li><a href="configs/ttsr/README.md">TTSR (CVPR'2020)</a></li>
          <li><a href="configs/glean/README.md">GLEAN (CVPR'2021)</a></li>
          <li><a href="configs/liif/README.md">LIIF (CVPR'2021)</a></li>
          <li><a href="configs/real_esrgan/README.md">Real-ESRGAN (ICCVW'2021)</a></li>
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
<tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Video Super-Resolution</b>
      </td>
      <td>
        <b>Video Interpolation</b>
      </td>
      <td>
        <b>Image Colorization</b>
      </td>
      <td>
        <b>Image Translation</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <ul>
            <li><a href="configs/edvr/README.md">EDVR (CVPR'2018)</a></li>
            <li><a href="configs/tof/README.md">TOF (IJCV'2019)</a></li>
            <li><a href="configs/tdan/README.md">TDAN (CVPR'2020)</a></li>
            <li><a href="configs/basicvsr/README.md">BasicVSR (CVPR'2021)</a></li>
            <li><a href="configs/iconvsr/README.md">IconVSR (CVPR'2021)</a></li>
            <li><a href="configs/basicvsr_pp/README.md">BasicVSR++ (CVPR'2022)</a></li>
            <li><a href="configs/real_basicvsr/README.md">RealBasicVSR (CVPR'2022)</a></li>
      </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/tof/README.md">TOFlow (IJCV'2019)</a></li>
          <li><a href="configs/cain/README.md">CAIN (AAAI'2020)</a></li>
          <li><a href="configs/flavr/README.md">FLAVR (CVPR'2021)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/inst_colorization/README.md">InstColorization (CVPR'2020)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/pix2pix/README.md">Pix2Pix (CVPR'2017)</a></li>
          <li><a href="configs/cyclegan/README.md">CycleGAN (ICCV'2017)</a></li>
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
<tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Inpainting</b>
      </td>
      <td>
        <b>Matting</b>
      </td>
      <td>
        <b>Text-to-Image</b>
      </td>
      <td>
        <b>3D-aware Generation</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <ul>
          <li><a href="configs/global_local/README.md">Global&Local (ToG'2017)</a></li>
          <li><a href="configs/deepfillv1/README.md">DeepFillv1 (CVPR'2018)</a></li>
          <li><a href="configs/partial_conv/README.md">PConv (ECCV'2018)</a></li>
          <li><a href="configs/deepfillv2/README.md">DeepFillv2 (CVPR'2019)</a></li>
          <li><a href="configs/aot_gan/README.md">AOT-GAN (TVCG'2019)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/dim/README.md">DIM (CVPR'2017)</a></li>
          <li><a href="configs/indexnet/README.md">IndexNet (ICCV'2019)</a></li>
          <li><a href="configs/mask2former">GCA (AAAI'2020)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="projects/glide/configs/README.md">GLIDE (NeurIPS'2021)</a></li>
          <li><a href="configs/guided_diffusion/README.md">Guided Diffusion (NeurIPS'2021)</a></li>
          <li><a href="configs/disco_diffusion/README.md">Disco-Diffusion (2022)</a></li>
          <li><a href="configs/stable_diffusion/README.md">Stable-Diffusion (2022)</a></li>
          <li><a href="configs/dreambooth/README.md">DreamBooth (2022)</a></li>
          <li><a href="configs/controlnet/README.md">ControlNet (2023)</a></li>
          <li><a href="configs/controlnet_animation/README.md">ControlNet Animation (2023)</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li><a href="configs/eg3d/README.md">EG3D (CVPR'2022)</a></li>
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

请参考[模型库](https://mmagic.readthedocs.io/zh_CN/latest/model_zoo/overview.html)了解详情。

<p align="right"><a href="#top">🔝返回顶部</a></p>

<<<<<<< HEAD
## 🤝 致谢
=======
- [x] [Global&Local](configs/inpainting/global_local/README.md) (ToG'2017)
- [x] [DeepFillv1](configs/inpainting/deepfillv1/README.md) (CVPR'2018)
- [x] [PConv](configs/inpainting/partial_conv/README.md) (ECCV'2018)
- [x] [DeepFillv2](configs/inpainting/deepfillv2/README.md) (CVPR'2019)
- [x] [AOT-GAN](configs/inpainting/AOT-GAN/README.md) (TVCG'2021)
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895

MMagic 是一款由不同学校和公司共同贡献的开源项目。我们感谢所有为项目提供算法复现和新功能支持的贡献者，以及提供宝贵反馈的用户。我们希望该工具箱和基准测试可以为社区提供灵活的代码工具，供用户复现现有算法并开发自己的新模型，从而不断为开源社区提供贡献。

<a href="https://github.com/open-mmlab/mmagic/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=open-mmlab/mmagic" />
</a>

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 🖊️ 引用

如果 MMagic 对您的研究有所帮助，请按照如下 bibtex 引用它。

<<<<<<< HEAD
```bibtex
@misc{mmagic2023,
    title = {{MMagic}: {OpenMMLab} Multimodal Advanced, Generative, and Intelligent Creation Toolbox},
    author = {{MMagic Contributors}},
    howpublished = {\url{https://github.com/open-mmlab/mmagic}},
    year = {2023}
}
```
=======
- [x] [SRCNN](configs/restorers/srcnn/README.md) (TPAMI'2015)
- [x] [SRResNet&SRGAN](configs/restorers/srresnet_srgan/README.md) (CVPR'2016)
- [x] [EDSR](configs/restorers/edsr/README.md) (CVPR'2017)
- [x] [ESRGAN](configs/restorers/esrgan/README.md) (ECCV'2018)
- [x] [RDN](configs/restorers/rdn/README.md) (CVPR'2018)
- [x] [DIC](configs/restorers/dic/README.md) (CVPR'2020)
- [x] [TTSR](configs/restorers/ttsr/README.md) (CVPR'2020)
- [x] [GLEAN](configs/restorers/glean/README.md) (CVPR'2021)
- [x] [LIIF](configs/restorers/liif/README.md) (CVPR'2021)

</details>

<details open>
<summary>视频超分辨率</summary>

- [x] [EDVR](configs/restorers/edvr/README.md) (CVPR'2019)
- [x] [TOF](configs/restorers/tof/README.md) (IJCV'2019)
- [x] [TDAN](configs/restorers/tdan/README.md) (CVPR'2020)
- [x] [BasicVSR](configs/restorers/basicvsr/README.md) (CVPR'2021)
- [x] [IconVSR](configs/restorers/iconvsr/README.md) (CVPR'2021)
- [x] [BasicVSR++](configs/restorers/basicvsr_plusplus/README.md) (CVPR'2022)
- [x] [RealBasicVSR](configs/restorers/real_basicvsr/README.md) (CVPR'2022)

</details>

<details open>
<summary>图像生成</summary>

- [x] [CycleGAN](configs/synthesizers/cyclegan/README.md) (ICCV'2017)
- [x] [pix2pix](configs/synthesizers/pix2pix/README.md) (CVPR'2017)

</details>

<details open>
<summary>视频插帧</summary>

- [x] [TOFlow](configs/video_interpolators/tof/README.md) (IJCV'2019)
- [x] [CAIN](configs/video_interpolators/cain/README.md) (AAAI'2020)
- [x] [FLAVR](configs/video_interpolators/flavr/README.md) (CVPR'2021)

</details>

请参考[模型库](https://mmediting.readthedocs.io/en/latest/_tmp/modelzoo.html)了解详情。

## 参与贡献

感谢您为改善 MMEditing 所做的所有贡献。请参阅 MMCV 中的 [CONTRIBUTING.md](https://github.com/open-mmlab/mmcv/blob/master/CONTRIBUTING.md) 以获取贡献指南。

## 致谢

MMEditing 是一款由不同学校和公司共同贡献的开源项目。我们感谢所有为项目提供算法复现和新功能支持的贡献者，以及提供宝贵反馈的用户。 我们希望该工具箱和基准测试可以为社区提供灵活的代码工具，供用户复现现有算法并开发自己的新模型，从而不断为开源社区提供贡献。

## 分支维护计划

MMCV 目前有两个分支，分别是 master 和 2.x 分支，它们会经历以下三个阶段：

| 阶段   | 时间                  | 分支                                                         | 说明                                                                                                     |
| ------ | --------------------- | ------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| 公测期 | 2022/9/1 - 2022.12.31 | 公测版代码发布在 1.x 分支；默认主分支 master 仍对应 0.x 版本 | master 和 1.x 分支正常进行迭代                                                                           |
| 兼容期 | 2023/1/1 - 2023.12.31 | **切换默认主分支 master 为 1.x 版本**；0.x 分支对应 0.x 版本 | 保持对旧版本 0.x 的维护和开发，响应用户需求，但尽量不引进破坏旧版本兼容性的改动；master 分支正常进行迭代 |
| 维护期 | 2024/1/1 - 待定       | 默认主分支 master 为 1.x 版本；0.x 分支对应 0.x 版本         | 0.x 分支进入维护阶段，不再进行新功能支持；master 分支正常进行迭代                                        |

## 引用

如果 MMEditing 对您的研究有所帮助，请按照如下 bibtex 引用它。
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895

```bibtex
@misc{mmediting2022,
    title = {{MMEditing}: {OpenMMLab} Image and Video Editing Toolbox},
    author = {{MMEditing Contributors}},
    howpublished = {\url{https://github.com/open-mmlab/mmediting}},
    year = {2022}
}
```

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 🎫 许可证

本项目开源自 [Apache 2.0 license](LICENSE)。

<p align="right"><a href="#top">🔝返回顶部</a></p>

<<<<<<< HEAD
## 🏗️ ️OpenMMLab 的其他项目

- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab MMEngine.
=======
- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab 深度学习模型训练基础库
>>>>>>> 6f2f3ae2ad3e365f94bbf19c01a1d1056dad3895
- [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab 计算机视觉基础库
- [MMEval](https://github.com/open-mmlab/mmeval): 统一开放的跨框架算法评测库
- [MIM](https://github.com/open-mmlab/mim): MIM 是 OpenMMlab 项目、算法、模型的统一入口
- [MMPreTrain](https://github.com/open-mmlab/mmpretrain): OpenMMLab 预训练工具箱
- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab 目标检测工具箱
- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab 新一代通用 3D 目标检测平台
- [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab 旋转框检测工具箱与测试基准
- [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab 语义分割工具箱
- [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab 全流程文字检测识别理解工具包
- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab 姿态估计工具箱
- [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 人体参数化模型工具箱与测试基准
- [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab 自监督学习工具箱与测试基准
- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab 模型压缩工具箱与测试基准
- [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab 少样本学习工具箱与测试基准
- [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab 新一代视频理解工具箱
- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab 一体化视频目标感知平台
- [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab 光流估计工具箱与测试基准
- [MMagic](https://github.com/open-mmlab/mmagic): OpenMMLab 新一代人工智能内容生成（AIGC）工具箱
- [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab 模型部署框架

<p align="right"><a href="#top">🔝返回顶部</a></p>

## 欢迎加入 OpenMMLab 社区

扫描下方的二维码可关注 OpenMMLab 团队的 [知乎官方账号](https://www.zhihu.com/people/openmmlab)，加入 OpenMMLab 团队的 [官方交流 QQ 群](https://jq.qq.com/?_wv=1027&k=K0QI8ByU)，或通过群主小喵加入微信官方交流群。

<div align="center">
<img src="docs/zh_cn/_static/image/zhihu_qrcode.jpg" height="500" />  <img src="https://user-images.githubusercontent.com/25839884/203927852-e15def4d-a0eb-4dfc-9bfb-7cf09ea945d0.png" height="500" /> <img src="https://raw.githubusercontent.com/open-mmlab/mmcv/master/docs/en/_static/wechat_qrcode.jpg" height="500" />
</div>

我们会在 OpenMMLab 社区为大家

- 📢 分享 AI 框架的前沿核心技术
- 💻 解读 PyTorch 常用模块源码
- 📰 发布 OpenMMLab 的相关新闻
- 🚀 介绍 OpenMMLab 开发的前沿算法
- 🏃 获取更高效的问题答疑和意见反馈
- 🔥 提供与各行各业开发者充分交流的平台

干货满满 📘，等你来撩 💗，OpenMMLab 社区期待您的加入 👬
