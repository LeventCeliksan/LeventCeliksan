# Levent Çeliksan
**Senior AI & Software Engineer** · Technical Founder of [Sealify](https://sealify.io) · Agentic AI · Computer Vision · AI Systems · Backend

Istanbul, Türkiye · Open to remote work · Open to relocating to the US (requires visa sponsorship)

**[Download my CV (PDF)](./Levent_Celiksan_CV.pdf)** · [LinkedIn](https://www.linkedin.com/in/levent-celiksan) · leventceliksan@gmail.com

---

Senior AI & Software Engineer and hands-on technical founder with 19+ years of backend and systems engineering, including leading and mentoring developers. Took Sealify from idea to public launch as its sole technical founder. Focused on applied AI engineering: production systems validated by measurement on real-world web data, agentic AI, computer vision, multimedia matching, KYC/identity verification, and content authentication.

### Sealify, Inc. · Technical Founder & Senior AI & Software Engineer (Nov 2023 – Present)
- Launched publicly in June 2026 as a multilingual (EN/TR/AR) SaaS platform; ~100 early users.
- 3,000+ measured test runs: 200,000+ candidate images scanned, 10,000+ verified matches across 5,000+ domains at ~98% precision in manual review.
- Self-hosted KYC: document template recognition, blink-based liveness and face matching (ID/passport vs. selfie, MRZ), saving ~$1 per verification.
- Audio-first originality check before registration, then fee-free Bitcoin timestamping via OpenTimestamps; 1,600+ registrations anchored on mainnet.
- Calibrated hybrid image/face matching (color/composition signals, InsightFace/ArcFace face gate, EfficientNet-B7): accuracy from ~60% to ~97%, on a queue-based, multi-instance architecture.
- Multi-engine reverse image/video search (Google Lens, Google Reverse Image, Yandex, Bing) with automatic failover; median 2.5 minutes to find copies, including cropped, recolored or re-titled versions.
- LangGraph research agent with local LLMs; autonomous Instagram/TikTok/YouTube monitors.
- Inventor on six US provisional patent applications (Patent Pending).
- Demo: https://www.youtube.com/watch?v=LIoTl1nJU5c · Intro: https://www.youtube.com/watch?v=Bh7kB-UIJhs

### Selected AI projects
- **[Aesthetic Detector, BEAUTY (Android)](https://github.com/LeventCeliksan/aesthetic-detector)**: CLIP ViT-B/16 fine-tuned on 1,000+ portraits, ONNX on-device inference, Kotlin.
- **AI Advertising Agency Automation**: 7-agent orchestrator; Python, FastAPI, Pydantic; multi-LLM routing (Gemini, Ollama, OpenRouter).

### Open-source tools (tested, installable)
Standalone, from-scratch tools that demonstrate the ideas behind my work, each with a test suite and a one-line install. They contain no Sealify or client code.

**Agentic AI & LLMs**
- **[local-dev-crew](https://github.com/LeventCeliksan/local-dev-crew)**: four CrewAI agents on a local Ollama model plan, write and syntax-check small Python projects inside a sandboxed folder.
- **[multi-llm-router](https://github.com/LeventCeliksan/multi-llm-router)**: task-based LLM routing across Gemini, OpenRouter and local Ollama with automatic failover on quota limits and outages.
- **[local-voice-assistant](https://github.com/LeventCeliksan/local-voice-assistant)**: talk to a local model, faster-whisper speech recognition, Ollama replies, per-user memory.

**Computer vision & media**
- **[scene-matcher](https://github.com/LeventCeliksan/scene-matcher)**: find photos of the same place or scene by ranking a folder on DINOv2 embedding similarity.
- **[phash-match](https://github.com/LeventCeliksan/phash-match)**: perceptual hashing to find resized, recompressed or recolored copies of images.
- **[ai-video-detector](https://github.com/LeventCeliksan/ai-video-detector)**: experimental 8-layer heuristic detector for AI-generated video.
- **[prompt-to-clip](https://github.com/LeventCeliksan/prompt-to-clip)**: generate an image with SDXL, refine it with a fixed seed, and animate it into a short clip.

**Content protection, identity & verification**
- **[ots-anchor](https://github.com/LeventCeliksan/ots-anchor)**: timestamp files on Bitcoin with no fees (OpenTimestamps) and verify against real block headers.
- **[lsb-watermark](https://github.com/LeventCeliksan/lsb-watermark)**: invisible LSB watermark IDs for images, with a checksum and folder/web search for marked copies.
- **[mrz-check](https://github.com/LeventCeliksan/mrz-check)**: offline ICAO 9303 passport/ID MRZ parser and check-digit validator (KYC).

### Earlier experience
Senior Software Engineer, BUBU / Kopuzlar Group (2018–2023) · Software Engineer, Artworks Lab AB (2015–2018) · Software Engineer, Yellow Pages / DataWorks (2012–2015) · Software Engineer, Jolly Tur (2008–2011) · Junior Software Engineer, REKLAMARKA (2006–2008)

### Tech
Python · FastAPI · PyTorch · ONNX Runtime · LangGraph · LangChain · RAG · Ollama · OpenCV · InsightFace · Kotlin · Node.js · PostgreSQL · MySQL · Redis · Docker · Kubernetes · AWS · GCP · Azure
