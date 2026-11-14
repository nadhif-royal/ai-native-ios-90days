# AI-Native iOS Engineering & AI Automation (90-Day Journey)

![Swift](https://img.shields.io/badge/Swift-6.0-F05138?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-iOS_18+-007AFF?style=flat&logo=apple&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=flat&logo=fastapi&logoColor=white)
![CoreML](https://img.shields.io/badge/CoreML-Edge_CV-34C759?style=flat&logo=apple&logoColor=white)

## Overview

This repository serves as a structured 90-day proof-of-work log (November 2026 – February 2027) bridging **AI Engineering**, **Business Workflow Automation**, and **Native iOS Development** ahead of joining the **Apple Developer Academy @ UC (Thamrin Nine, Jakarta)** in February 2027.

Rather than treating mobile development and artificial intelligence as separate tracks, every milestone in this repository converges toward building **AI-Native iOS Applications**—combining on-device computer vision (`Core ML` + `Vision`), structured LLM orchestration (`Gemini API` + `FastAPI`), and modern declarative interfaces (`Swift 6` + `SwiftUI`).

---

## 90-Day Engineering Roadmap

| Phase | Timeline | Core Domain | Key Deliverables |
| :--- | :--- | :--- | :--- |
| **Phase 1** | Days 1–30 | AI Automation, FastAPI & Edge-CV | Automated Instagram Carousel Engine (`Pusbisnas`), async `FastAPI` AI service, and `.mlpackage` quantized CV model |
| **Phase 2** | Days 31–60 | Swift 6 Language & Algorithms | Mastery of Swift 6 strict concurrency, ARC memory management, and 20+ LeetCode solutions in Swift |
| **Phase 3** | Days 61–90 | SwiftUI Architecture & Apple Vision | MVVM app architecture, `URLSession` API integration, and real-time `AVFoundation` + `Core ML` prototype |

---

## Repository Architecture

```text
ai-native-ios-90days/
├── 01-pusbisnas-auto-design/      # HTML/Tailwind + Jinja2 + Gemini API + Playwright slicer
│   ├── templates/                 # Executive Prestige 4:5 carousel templates
│   ├── assets/                    # Background-removed visual assets (rembg)
│   └── auto_pusbisnas.py          # End-to-end CLI content & image generator
├── 02-fastapi-ai-backend/         # Production async REST API & RAG workflow
├── 03-edge-cv-coreml/             # PyTorch/ONNX to Apple .mlpackage conversion scripts
├── 04-swift6-fundamentals/        # Swift 6 syntax, Concurrency, ARC notes & LeetCode
└── 05-swiftui-vision-prototype/   # Pre-Academy iOS architecture & Vision blueprint

```

---

## Proof-of-Work Tracker

### Phase 1: AI Automation, FastAPI & Edge-CV (Days 1–30)

* [ ] Build and deploy `auto_pusbisnas.py` with HTML5/Tailwind templates, Gemini structured outputs, and Playwright auto-slicing
* [ ] Wrap LLM & RAG workflows into an asynchronous REST API using `FastAPI` and `Pydantic`
* [ ] Convert custom object detection weights (PyTorch/YOLOv5s) into Apple's `.mlpackage` format with FP16/INT8 quantization via `coremltools`

### Phase 2: Swift 6 Language & Algorithms (Days 31–60)

* [ ] Complete Days 1–15 of *100 Days of SwiftUI* (Optionals, Value vs. Reference Types, Protocols, Generics, Closures)
* [ ] Document Swift Concurrency patterns (`async/await`, `Task`, `Actors`) and ARC leak prevention (`weak`/`unowned`)
* [ ] Solve 20 algorithmic problems on LeetCode using Swift

### Phase 3: SwiftUI & On-Device Vision (Days 61–90)

* [ ] Complete Stanford CS193p Lectures 1–8 covering reactive state (`@State`, `@Observable`) and MVVM architecture
* [ ] Implement type-safe networking in Swift using `URLSession` and `Codable` connected to the Phase 1 `FastAPI` backend
* [ ] Architect the camera pipeline (`AVFoundation` + `Vision` + `Core ML`) ready for immediate Xcode compilation at the Academy

---

## Quick Start: Pusbisnas Auto-Design Engine

### 1. Environment Setup

```bash
pip install google-genai playwright jinja2 pillow pydantic rembg
playwright install chromium

```

### 2. Generate 4:5 Instagram Carousel & Caption

```bash
export GEMINI_API_KEY="your_api_key_here"
python 01-pusbisnas-auto-design/auto_pusbisnas.py \
  --topik "3 Kesalahan Fatal Menyusun Customer Segments di Business Model Canvas" \
  --slides 5

```

---

## Author

**Nadhif Rif'at Rasendriya**

*Informatics Engineering Undergraduate — Universitas Brawijaya*

*Incoming Cohort 2027 — Apple Developer Academy @ UC (Jakarta)*

GitHub: [@nadhif-royal](https://github.com/nadhif-royal)
