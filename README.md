<p align="center">
  <img src="oregon-trail.svg" alt="oregon trail pixel animation" width="800"/>
</p>

<p align="center">
  <img src="https://gifdb.com/images/high/hacker-screen-mastermind-pixel-jeff-nt0m8sakkytx3b8m.gif" width="480" alt="pixel coder"/>
</p>

<h1 align="center">hey, I'm Amadeo 👋</h1>

<p align="center">
  I build things at the intersection of hardware and software.<br/>
  Custom inference engines, iOS apps with AI backends, automation that runs itself.
</p>

<br/>

- 🔩 currently working on: LLM inference that streams weights off NVMe directly to GPU on Jetson Orin Nano
- ⚡ fun fact: I beat Claude Opus 4.5 on Anthropic's own kernel optimization benchmark — **1,358 cycles vs 1,363**
- 🌿 shipped: a full iOS plant ID app with vision AI, Supabase backend, and a Claude-powered chat
- 🎬 also built: an automated video pipeline that generates, quality-gates, and delivers reels via Telegram
- 📫 reach me: **abonde421@gmail.com**

<br/>

### 🛠 tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**AI / ML**

![Claude API](https://img.shields.io/badge/Claude_API-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![CUDA Kernels](https://img.shields.io/badge/CUDA_Kernels-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Mobile / Backend**

![SwiftUI](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-000000?style=flat-square&logo=deno&logoColor=white)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)

<br/>

### 📌 projects

| | |
|---|---|
| [**jetson-inference**](https://github.com/amadeobonde/jetson-inference) | LLM inference engine for Jetson Orin Nano — streams quantized weights off NVMe via `io_uring`, custom CUDA kernels, sparse FFN activation prediction cuts I/O ~60% · `C++` `CUDA` |
| [**HerbLens**](https://github.com/amadeobonde/HerbLens) | iOS plant identification app — camera → instant ID → AI chat, SwiftUI + Supabase + Gemini vision + Claude · `Swift` `Supabase` |
| [**anthropic-kernel-challenge**](https://github.com/amadeobonde/anthropic-kernel-challenge) | Optimized Anthropic's VLIW SIMD scheduler to 1,358 cycles, beating Claude Opus 4.5 (1,363). DAG scheduling, WAR hazard elimination, SIMD vectorization · `Python` |
| [**devexana-reels**](https://github.com/amadeobonde/devexana-reels) | Automated Instagram Reels pipeline — 6 video formats, Gemini AI captions, quality gate, Telegram review bot · `Python` `MoviePy` `Remotion` |
