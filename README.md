# Levent Çeliksan
**Technical Founder & Senior Principal AI Engineer — [Sealify, Inc.](https://sealify.io)**

Istanbul, Türkiye · Open to remote work · Open to relocating to the U.S.

[LinkedIn](https://www.linkedin.com/in/levent-celiksan) · leventceliksan@gmail.com

---

Senior AI & Software Engineer and technical founder with 19+ years of experience building backend, infrastructure, and production software systems, including leading and mentoring engineers. Built and launched Sealify end to end as its sole technical founder, owning product architecture, backend engineering, applied AI, infrastructure, security, and operations.

Inventor on six U.S. provisional patent applications in AI-driven content protection, deepfake detection, and multimedia matching. Invited to participate in IPHatch North America 2026 with Sealify; the program is currently ongoing and final results are pending.

Specialties: custom computer vision algorithms on open-source models, agentic AI with local LLMs, and self-hosted AI infrastructure.

### Sealify, Inc. · Technical Founder & Senior Principal AI Engineer (Nov 2023 – Present)
- **Product:** Launched in June 2026 as a multilingual (EN/TR/AR) SaaS platform with ~100 early users: Google sign-in, subscription plans (free to $200/month) with crypto payments, a user dashboard, and an admin panel with scheduled DMCA scans and user-approved takedown notices.
- **Measured results:** 3,000+ test runs; 200,000+ candidate images scanned and 10,000+ verified matches identified across 5,000+ domains at ~98% precision in manual review; a single video test found 1,050+ matches across 80+ domains; 10,000+ media items (450+ GB) archived automatically.
- **Reverse image/video search:** Designed a two-stage reverse search: multi-engine retrieval (Google Lens, Google Reverse Image, Yandex, Bing) with automatic failover, then local verification. Finds public copies across the web in a median of 2.5 minutes, including resized, recolored, restyled, or audio-altered versions.
- **Matching engine:** Designed a custom multi-signal matching algorithm (color distribution, dominant palette, background, lighting, pHash, EfficientNet-B7 embeddings) gated by InsightFace/ArcFace face verification; calibrating its weights and thresholds raised matching accuracy from ~60% to ~97%. Runs on parallel workers in a queue-based, multi-instance architecture.
- **Self-hosted KYC:** Designed a multi-stage identity verification pipeline: custom template-based document recognition, blink-based liveness check, and face matching with open-source models, saving ~$1 per verification vs. paid providers. Correctly verified 20/20 users in a pilot test.
- **Novelty check & Bitcoin timestamping:** Audio-first novelty check before registration; approved content is anchored to Bitcoin via OpenTimestamps as a fingerprint manifest (SHA-256 + pHash of 27 frames × 12 crop/rotation variants). 1,600+ registrations anchored on mainnet, with independently verifiable timestamp proofs.
- **Autonomous monitoring:** Workers check users' connected Instagram, TikTok, and YouTube channels every 15 minutes; a piracy-site monitor feeds new titles into the detection pipeline; a LangGraph agent with local LLMs investigates suspected piracy sites and writes evidence-based reports.
- **Deepfake detection & NCII discovery:** Prototyped a hybrid detector for AI-generated images and videos (custom image-analysis signals plus voting across Hugging Face classifiers); built a victim-protection feature on top of the reverse search and face-verification pipeline, shipped in paid plans.
- **Infrastructure & cost:** Production on self-hosted hardware behind Cloudflare; bootstrapped and fully remote, with no office or paid LLM APIs: ~$300/year in recurring service costs.
- Demo: https://www.youtube.com/watch?v=LIoTl1nJU5c · Intro: https://www.youtube.com/watch?v=Bh7kB-UIJhs

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

### Earlier experience
- **Senior Software Engineer — BUBU (Kopuzlar Group)**, Türkiye (2018–2023): Set technical direction and led 2 developers; built Python APIs, e-commerce backends, and LLM/RAG integrations (2023); ran production infrastructure with Docker, CI/CD, monitoring, and backups.
- **Software Engineer — Artworks Lab AB**, Stockholm, Sweden (Remote) (2015–2018): Boutique e-commerce agency: led backend development and built Django/DRF e-commerce systems, using Elasticsearch, Redis, and AWS to support search, caching, and high-traffic campaigns.
- **Software Engineer — Yellow Pages / DataWorks**, United States (Remote) (2012–2015): U.S. local search and digital marketing company: developed business-listing, mapping/geocoding, and caller-ID services, including REST APIs and backend systems using PHP/Laravel, MySQL, and AWS.
- **Software Engineer — Jolly Tur**, Istanbul, Türkiye (2008–2011): Major Turkish travel company: developed PHP/MySQL booking and e-commerce backends, SOAP/XML supplier integrations, and supported Linux/Windows server infrastructure.
- **Junior Software Engineer — REKLAMARKA**, Türkiye (2006–2008): Digital agency: developed corporate websites, PHP/MySQL backends, admin panels, and e-commerce integrations for client projects.

### Tech
Python · FastAPI · PyTorch · ONNX Runtime · LangGraph · LangChain · RAG · Ollama · OpenCV · InsightFace · Kotlin · Node.js · PostgreSQL · MySQL · Redis · Docker · Kubernetes · AWS · GCP · Azure
