# Levent Çeliksan
**Technical Founder & Senior Principal AI Engineer — [Sealify, Inc.](https://sealify.io)**

Istanbul, Türkiye · Open to remote work · Open to relocating to the U.S.

[LinkedIn](https://www.linkedin.com/in/levent-celiksan) · leventceliksan@gmail.com

---

Senior AI & Software Engineer and technical founder with 19+ years of experience building backend, infrastructure, and production software systems, including leading and mentoring engineers. Built and launched Sealify end to end as its sole technical founder, owning product architecture, backend engineering, applied AI, infrastructure, security, and operations.

Inventor on six U.S. provisional patent applications in AI-driven content protection, deepfake detection, and multimedia matching. Invited to participate in IPHatch North America 2026 with Sealify; the program is currently ongoing and final results are pending.

Specialties: custom computer vision algorithms on open-source models, agentic AI with local LLMs, and self-hosted AI infrastructure.

### Sealify, Inc. · Technical Founder & Senior Principal AI Engineer (Nov 2023 – Present)

- **Product:** Launched a multilingual (EN/TR/AR) SaaS platform in June 2026, with approximately 100 registered early users during testing. Built the complete product experience, including Google sign-in, subscription management, crypto payments, user dashboards, and administrative tools for automated content monitoring and user-approved takedown workflows.

- **Measured results:** Conducted 3,000+ test runs; evaluated 200,000+ candidate images and identified 10,000+ verified matches across 5,000+ domains, achieving approximately 98% precision in manual review. A single video test identified 1,050+ matches across 80+ domains. Automatically archived 10,000+ media items totaling 450+ GB.

- **AI-powered content protection:** Designed and developed an automated content discovery and verification system that identifies potentially unauthorized copies of protected media across public online sources. Achieved a median detection time of 2.5 minutes and supports the identification of significantly modified media, including resized, cropped, recolored, and altered video content.

- **Media intelligence engine:** Developed a custom media verification and matching engine. Improved internal matching accuracy from approximately 60% to 97% through extensive testing, evaluation, and calibration. Designed the system to process large volumes of media efficiently.

- **Self-hosted identity verification:** Designed and implemented an in-house identity verification solution, reducing estimated costs by approximately $1 per verification compared with commercial providers. Successfully verified 20 out of 20 users in a pilot test.

- **Digital ownership & verification:** Developed a content registration and originality verification system with independently verifiable Bitcoin mainnet timestamp proofs. Successfully registered and anchored 1,600+ records on Bitcoin mainnet.

- **Automated monitoring & reporting:** Built autonomous monitoring capabilities for connected social media accounts and selected online sources. Developed AI-assisted investigation and evidence-based reporting workflows to support copyright enforcement and content protection.

- **Deepfake protection & NCII discovery:** Prototyped AI-generated image and video detection capabilities. Developed a victim-protection feature to help identify potentially non-consensual intimate imagery (NCII), included in paid subscription tiers.

- **Infrastructure & operations:** Bootstrapped and operated a cost-efficient production environment behind Cloudflare, with approximately $300/year in recurring service costs at the current scale. Built and maintained the platform independently, without external funding or a dedicated engineering team.

- **Demo:** https://www.youtube.com/watch?v=LIoTl1nJU5c  
- **Introduction:** https://www.youtube.com/watch?v=Bh7kB-UIJhs

### Writing
- **[How I find edited copies of images across the web without crawling it](https://leventceliksan.github.io/copy-detection/)** (Sep 2026): public search indexes as the first stage of copy detection, every match verified locally, with a real 761 → 643 test run.

### Patent applications
Six U.S. provisional patent applications (USPTO, Nov–Dec 2025, Patent Pending), including content tracking and protection (63/923,341); real-time deepfake detection (63/923,358); multimodal novelty assessment (63/923,342); autonomous video registration (63/934,369); multimedia semantic equivalence (63/946,066).

### Selected AI projects
- **[Aesthetic Detector, BEAUTY (Android)](https://github.com/LeventCeliksan/aesthetic-detector)**: CLIP ViT-B/16 fine-tuned on 1,000+ portrait photos, converted to ONNX and optimized for on-device inference (~2 seconds); multi-stage scoring with EfficientNet-B0 regional analysis; Kotlin app with a Node.js/Express/MySQL backend.
- **AI Advertising Agency Automation**: 7 agents coordinated by a manager agent; a single LLM gateway in Python using FastAPI and Pydantic with Gemini model tiers, local Ollama fallback, and OpenRouter; deterministic checks plus vision-model review for quality control.

### Open-source tools (tested, installable)
Most of my production work, including Sealify and client systems, lives in private codebases. In September 2026 I published standalone versions of tools I had built over the years: each has a test suite and a one-line install, and none contains Sealify or client code.

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

### Tech
Python · FastAPI · PyTorch · ONNX Runtime · LangGraph · LangChain · RAG · Ollama · OpenCV · InsightFace · Kotlin · Node.js · PostgreSQL · MySQL · Redis · Docker · Kubernetes · AWS · GCP · Azure
