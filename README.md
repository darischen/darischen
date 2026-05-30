# Daris Chen

**San Francisco/San Diego/Los Angeles, CA** | [LinkedIn](https://linkedin.com/in/darischen) | [Personal Site](https://darischen.com) | [Email](mailto:daris.chen@gmail.com)

B.S. Computer Engineering, UC San Diego. Building across AI/ML, frontend, backend, systems, and research.

---

## 🚀 Featured Project: FlipperZillow

AI house tour platform transforming real estate images into immersive 3D experiences. Computer vision pipeline (DepthAnythingV2 → DFormerV2 → SAM3D) on AMD ROCm. Claude API for semantic property analysis, ElevenLabs narration. Frontend: Next.js, Three.js, WebSpatial (Vision Pro).

**Tech:** Next.js, Python, PyTorch, AMD ROCm, Three.js, WebSpatial, Claude API  
[View on GitHub](https://github.com/darischen/FlipperZillow)

---

## AI/ML

Building intelligent systems from game engines to job automation.

### Mini-Stockfish
Chess engine with NNUE evaluation. Bitboard move generation, alpha-beta minimax with iterative deepening and quiescence search, transposition tables with MVV-LVA move ordering. Evaluator trained on 16 million Stockfish-annotated positions.

**Tech:** Python, C++, PyTorch  
[Repo](https://github.com/darischen/Mini-Stockfish)

### Career-Ops Pipeline
Multi-agent batch job application system with three-tier conductor-worker-judge pipeline. Playwright extraction serialization, parallel worker subagents with Anthropic prompt caching of CV/resume PDFs, background judge enforces structured schema. Two-phase resume variant selection on 10-point scoring lead.

**Tech:** Python, Node.js, Anthropic SDK, Playwright  
[Repo](https://github.com/darischen/career-ops)

### EEWS (Elon Early Warning System)
Stock prediction with LSTM RNN trained on Yahoo Finance historical data. Technical indicators (Bollinger Bands, MACD, EMA, SMA, VIX). GPU acceleration via CUDA.

**Tech:** Python, PyTorch, CUDA  
[Repo](https://github.com/darischen/EEWS)

---

## Frontend

Shipping production web applications across e-commerce, SaaS, and personal projects.

### gw-website-react
Next.js e-commerce platform for Groundwork Books. API routes for order processing, event management, semantic search (Pinecone), third-party integrations (Square POS, Instagram, Google Sheets). Redis caching (90% latency reduction), request coalescing for concurrent inventory lookups.

**Tech:** TypeScript, Next.js, Firebase, Pinecone, Redis  
[Repo](https://github.com/darischen/gw-website-react)

### weatherapp
Weather application with geolocation, real-time data, and interactive maps.

**Tech:** TypeScript, Next.js, PostgreSQL  
[Repo](https://github.com/darischen/weatherapp)

### dchen
Personal portfolio website.

**Tech:** Next.js, TypeScript, TailwindCSS  
[Repo](https://github.com/darischen/dchen)

---

## Backend

Building scalable APIs and services with focus on data infrastructure.

### PatentIQ
AI-powered patent search and drafting assistant. Semantic search via pgvector embeddings over USPTO dataset. FastAPI backend with Auth0 OAuth2, Claude/OpenAI LLM integration for patent analysis and drafting. Deployed Vercel frontend + EC2 backend.

**Tech:** FastAPI, PostgreSQL pgvector, Auth0, OpenAI, Claude, Supabase, EC2  
[Repo](https://github.com/darischen/PMA)

---

## DevOps

Serverless-first deployment (Vercel frontend + API routes), automatic CI/CD. Infrastructure: Vercel, EC2, PostgreSQL, Supabase, Firebase.

**Tech:** Vercel, GitHub Actions, EC2, Docker  

---

## Research

Novel systems and reproductions of cutting-edge research.

### HB100 Phased Array Radar
4-element Doppler radar array (10.525 GHz). ESP32-S3 collects ADC samples over USB-CDC. Raspberry Pi 4 runs DSP chain: Butterworth bandpass filter, Hanning-windowed FFT, MUSIC angle-of-arrival estimation with spatial smoothing, Extended Kalman Filter tracking (x, y, vx, vy).

**Tech:** C, Python, Signal Processing  
[Repo](https://github.com/darischen/PhasedArrayRadar)

### FishSense (UCSD E4E)
Custom R-CNN training pipeline (ResNet-50) for underwater laser-profiling. Dual-laser photogrammetry algorithm extracts biological metrics (fish length/mass) from 2D video. Sub-5% error on pixel-to-centimeter conversion.

**Tech:** Python, PyTorch, Detectron2  

### RedShift
LLM jailbreaking research reproducing adversarial prompt engineering. DeBERTa finetuning, adversarial attack generation, benchmarking across language models.

**Tech:** Python, PyTorch, DeBERTa  
[Repo](https://github.com/darischen/RedShift)

---

## Other Projects

- **Simplerfy** — [Repo](https://github.com/darischen/Simplerfy)
- **8-bit CPU** — [Repo](https://github.com/darischen/8bitCPU)
- **16-bit Adder** — [Repo](https://github.com/darischen/16bitAdder)

---

## Get in Touch

- [Email](mailto:daris.chen@gmail.com)
- [LinkedIn](https://linkedin.com/in/darischen)
- [Personal Site](https://darischen.com)
- [GitHub](https://github.com/darischen)
