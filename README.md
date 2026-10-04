# iClovers Tensor Player 🎬⚡

> **Breaking the single-window paradigm: A multimodal media workstation powered by fluid physics layout and tensor-grade computer vision.**  
> *打破传统播放器的“单一视窗”牢笼 —— 基于流体物理排版与计算级 AI 的多模态多媒体工作台。*

[![Language](https://img.shields.io/badge/Language-C%2B%2B17%2F20-blue.svg)](https://en.cppreference.com/)
[![Framework](https://img.shields.io/badge/Framework-Qt%206-green.svg)](https://www.qt.io/)
[![Engine](https://img.shields.io/badge/Render-MDK%20%7C%20RHI%20%7C%20FFmpeg-orange.svg)](https://github.com/wang-bin/mdk-sdk)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)]()
[![License](https://img.shields.io/badge/License-GPLv3%20%2F%20Commercial-brightgreen.svg)]()

[English Overview](#-english-overview) | [简体中文](#-中文简介)
[Video Overview](https://www.bilibili.com/video/BV1b5e16FEF8/?vd_source=f43a4085c7e21579fa851ae0b515ab55)
---

## 🇬🇧 English Overview

### 🌟 Why Tensor Player?
For decades, mainstream media players have adhered to a monolithic paradigm: a black frame, a static seek bar, and the linear playback of a single media file. However, modern workflows demand far more:
- **Multimodal Comparison**: Synchronizing multi-angle camera feeds alongside text documentation, code, and reference imagery.
- **Micro-Analysis & Review**: Looping multiple non-contiguous segments inside a single lecture, dance rehearsal, or surveillance feed.
- **In-Stream Vision Inspection**: Extracting raw pixel channels, enhancing visibility, or tracking moving targets in real-time without re-rendering in external NLEs.

**iClovers Tensor Player** breaks the "single-window cage." It is not merely a player, but a multimodal vision workbench combining a **fluid layout engine**, **multi-range loop control**, and **tensor-level computer vision pipelines**.

---

### ✨ Key Features

- 🧩 **Fluid Physical Layout Engine**
  - **Responsive Grid**: Built on an automated pathfinding and physical-avoidance layout algorithm with automatic compaction.
  - **Freeform Canvas**: Pack selected media windows into floating, zoomable canvas boards for flexible multi-window arrangements.
- 🔁 **Multi-Range A-B Loop Playback**
  - Eliminates the constraint of conventional single-pair $[A, B]$ repeat loops.
  - Mark multiple distinct time segments across the timeline; the playback engine automatically skips intermediate gaps, stitches segments seamlessly, and loops continuously.
- 📺 **Surveillance-Grade Video Wall Matrix**
  - Instant switching across 2x2, 3x3, center-focused, and absolute seamless stitching layouts.
  - **Sub-Grid Nesting**: Automatically folds overflowing channels into nested sub-grids without breaking geometric layout constraints.
  - Native support for RTSP streaming, ONVIF PTZ cameras, and automated directory radar monitoring.
- 👁️ **Real-Time Tensor-Grade Vision Algorithms**
  - **Image Enhancement**: Dark Channel Prior (DCP) dehazing, adaptive low-light enhancement, Retinex SSR, and CLAHE.
  - **Color Channel Decomposition**: Split running video streams into synchronous 2x2 / 3x2 matrices of RGB, YUV, HSV, CIELAB, or color-blindness simulation modes.
  - **Live Target Perception**: CSRT tracking (with auto-framing and zoom-in tracking), YOLO object detection, OCR subtitle extraction, and instant QR/barcode decoding.
- 🛠️ **End-to-End Post-Production Loop**
  - Attach auxiliary background audio tracks, segment-based progress bar watermarks (.pgwm), and vector ASS subtitles.
  - Powered by embedded FFmpeg pipelines for transition-rich rendering (xfade/acrossfade), format remuxing, and frame extraction directly within the workstation.

---

## 🇨🇳 中文简介

### 🌟 为什么选择 Tensor Player？
几十年来，主流播放器始终停留在“一个黑框、一条进度条、按部就班播放一个文件”的传统范式。但在实际的创作与技术工作中：
- **素材对比**：需要一边核对机位画面，一边查阅工程文档和参考图；
- **片段精读**：想要针对同一个长视频圈选多个不同时间段进行跳跃、反复循环复盘；
- **视觉分析**：面对恶劣光线或特定通道信息，传统播放器无法在播放中实时拆解与增强像素底层信息。

**iClovers Tensor Player** 颠覆了这一现状——它不仅是一个高性能的跨格式播放器，更是一个融合了**流体网格排版**、**多区间循环引擎**与**工业级视觉计算（Tensor）**的多模态视讯工作台。

---

### ✨ 核心特性

- 🧩 **动态流体物理排版引擎**
  - **自研弹性网格**：媒体拖拽自动寻路、物理避让与紧凑紧缩（Compact 算法）。
  - **自由画布（Canvas）**：支持将任意数量的音视频、文本及网页组合一键升格为悬浮画布，实现无缝拖拽与图层管理。
- 🔁 **多区间独立循环（Multi-Range A-B Loop）**
  - 突破传统播放器单次只能设一组 $[A, B]$ 的限制。
  - 支持在单条时间轴上圈选多个时间片段，自动跳跃、平滑衔接并整体循环，专为动作拆解、舞蹈扒舞、网课精听设计。
- 📺 **专业级安防电视墙矩阵**
  - 支持 2x2、3x3、中心主讲与绝对无缝拼接等多种矩阵布局。
  - **防溢出嵌套算法**：超出显示限制时自动将多余画面折叠为子电视墙，严防溢出崩溃。
  - 支持 RTSP 网络串流、ONVIF 摄像机接入与文件夹动态雷达监视。
- 👁️ **实时 Tensor 视觉与算法解构**
  - **画质增强**：暗通道先验去雾（DCP）、自适应夜视、Retinex 反射率增强与自适应直方图（CLAHE）。
  - **多维色彩解构**：播放中实时拆解为 RGB、YUV、HSV、CIELAB 及色盲模拟矩阵。
  - **智能视讯感知**：内置 CSRT 目标跟踪（支持自动平滑跟拍放大）、YOLO 目标检测、实时 OCR 字幕抓取与二维码秒级识别。
- 🛠️ **从“观看”到“产出”的后期闭环**
  - 支持注入外挂第二背景音频轨、分段进度条水印（.pgwm）与 ASS 矢量字幕渲染。
  - 内置基于 FFmpeg 管道的视频合并、转场特效渲染（xfade/acrossfade）与高帧率无损图片序列切解。
