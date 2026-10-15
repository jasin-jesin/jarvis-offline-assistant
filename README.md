# 🎙️ Jarvis — Fully Offline Voice Assistant

> Ubuntu · 12 V hardware · Whisper · Llama 3.1 (Ollama) · Piper TTS · OpenWakeWord

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Offline](https://img.shields.io/badge/cloud-none-lightgrey)

<!-- TODO: hardware photo -> media/hero.jpg -->
<!-- TODO: demo video with audio (link a YouTube/LinkedIn video here) -->

## Overview

A personal assistant that runs completely offline on a 12 V Ubuntu machine. No audio or text leaves the device.

## Pipeline

```
Mic → OpenWakeWord → Whisper (speech-to-text) → Llama 3.1 via Ollama → Piper (text-to-speech) → Speaker
```

<!-- TODO: replace with a drawn pipeline diagram -> media/pipeline.png -->

## Stack

| Stage | Tool |
|---|---|
| Wake word | OpenWakeWord |
| Speech-to-text | Whisper |
| Language model | Llama 3.1 on Ollama |
| Text-to-speech | Piper |
| OS | Ubuntu |

## Roadmap

- [x] End-to-end offline voice loop
- [ ] Smart routing between fast and slow paths
- [ ] Tool integrations (home control, timers, notes)

## Setup

<!-- TODO: install steps, models to pull, how to run -->

## Author

**Jasin Jesin** · [LinkedIn](https://www.linkedin.com/in/jasinjesin/)
