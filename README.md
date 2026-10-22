# Atoll for Windows

Atoll is an offline text and document translator by **4pp Studio**.
The Windows portable ZIP includes the app, runtime, and Tencent HY-MT2 1.8B Q4_K_M model.

**Website:** https://atoll-one.vercel.app

**Download:** [Atoll-Windows-x64.zip](https://github.com/Fthkrks/atoll-releases/releases/latest/download/Atoll-Windows-x64.zip)

Unzip the entire **Atoll** folder and run **Atoll.exe**. No installer, Ollama setup,
separate .NET install, administrator access, or model download is needed.

## System requirements

- Windows 10 version 2004 (build 19041) or newer / Windows 11, x64.
- 8 GB RAM recommended. CPU inference with automatic AVX selection; no dedicated GPU required.
- Download: **1,193,218,824 bytes (1.19 GB / 1.111 GiB)**.
- Extracted: **1,346,464,930 bytes (1.35 GB)**.
- Keep at least **2.6 GB free** for the ZIP and extracted folder together
  (exact combined file sizes: 2,539,683,754 bytes). The ZIP can be deleted after extraction.
- Optional PDF OCR uses locally installed Windows OCR language packs.

Settings and logs are stored in `%LOCALAPPDATA%\HyTranslate`.
Translation uses the built-in engine by default and works offline.
The Settings page offers an optional Ollama backend and a local GGUF file picker.

## Licenses and attribution

The model is an unmodified copy of Tencent's official HY-MT2-1.8B Q4_K_M GGUF.
Copyright (C) 2026 Tencent. All rights reserved.
The current official license for these exact weights is **Apache License 2.0**.
It has no EU, UK, or South Korea exclusion. See [LICENSES/NOTICE.txt](LICENSES/NOTICE.txt)
for pinned upstream sources, the matching model hash, and redistribution conditions.
Redistribution requires the license and applicable attribution/NOTICE texts; modified
files must carry change notices. No model weights were modified for this release.

LLamaSharp 0.30.0 and llama.cpp use the MIT license. Full third-party license texts,
including .NET, Windows App SDK, and Visual C++ Runtime terms, are in [LICENSES](LICENSES).
Atoll is not endorsed by Tencent or Microsoft. The software is provided without warranty.

This repository contains only release documentation and license notices.
Application source code and model weights are not committed here. Downloads are release assets.
