# Daris Chen

**San Francisco/San Diego/Los Angeles, CA** | [LinkedIn](https://linkedin.com/in/darischen) | [Personal Site](https://darischen.com) | [Email](mailto:daris.chen@gmail.com)

B.S. Computer Engineering, UC San Diego. Building across AI/ML, frontend, backend, systems, and research.

---

## 🚀 Featured Project: FlipperZillow

AI house tour platform combining 3D UI innovation, ML vision pipeline, and backend orchestration.

**What it does:** Transforms real estate images into immersive 3D experiences. Processes property photos through a computer vision pipeline (DepthAnythingV2 → DFormerV2 → SAM3D), generates AI-written property scripts with narration, and renders interactive 3D tours with Vision Pro support.

**Tech Stack:**
- **Frontend:** Next.js, Three.js, WebSpatial, Google Maps
- **Backend:** Python, FastAPI, AMD ROCm GPU pipeline
- **AI:** Claude API (semantic analysis), DepthAnythingV2, DFormerV2, SAM3D, ElevenLabs

[View on GitHub](https://github.com/darischen/FlipperZillow)

---

## AI/ML

Building intelligent systems from game engines to job automation.

### Mini-Stockfish
Hybrid chess engine combining HalfKP NNUE neural networks with advanced alpha-beta search (killer moves, counter-move heuristics, quiescence search, NMP, LMR). Optimized via Cython and C++ move generation, reducing evaluation latency by 77.2% on commodity hardware.

**Tech:** Python, C++, PyTorch, NumPy  
[Repo](https://github.com/darischen/Mini-Stockfish)

### Career-Ops Pipeline
Multi-agent batch job application system with three-tier conductor-worker-judge pipeline. Serializes Playwright extraction to prevent race conditions while parallel worker subagents generate outputs and a background judge enforces structured schema. Reduces token cost through Anthropic prompt caching of CV and 4 resume PDFs, with intelligent resume variant selection (10-point lead threshold).

**Tech:** Python, Node.js, Anthropic SDK, Claude, Playwright, Prompt Caching  
[Repo](https://github.com/darischen/career-ops) (fork from santifer/career-ops with custom apply instructions)

### EEWS (Elon Early Warning System)
Stock prediction model using LSTM RNN trained on historical stock data from Yahoo Finance. Features technical indicator support (Bollinger Bands, MACD, EMA, SMA, VIX) with GPU acceleration via CUDA.

**Tech:** Python, PyTorch, CUDA, TensorFlow  
[Repo](https://github.com/darischen/EEWS)

---

## Frontend

Shipping production web applications across e-commerce, SaaS, and personal projects.

### gw-website-react
Full-stack Next.js e-commerce platform for Groundwork Books. Backend API routes handle order processing, event management, semantic search, and third-party integrations (Square POS, Instagram, Google Sheets). Features Redis caching (90% latency reduction on Square API calls), Pinecone vector search across 4,000+ SKUs, and request coalescing for concurrent inventory lookups.

**Tech:** TypeScript, Next.js, React, TailwindCSS, Firebase Auth, Pinecone, Redis  
[Repo](https://github.com/darischen/gw-website-react)

### weatherapp
Full-stack weather application with geolocation integration and multiple mapping APIs. Real-time weather data, user location services, and interactive map interfaces.

**Tech:** TypeScript, Next.js, React, PostgreSQL  
[Repo](https://github.com/darischen/weatherapp)

### dchen
Personal portfolio and resume website showcasing projects and professional background.

**Tech:** Next.js, TypeScript, TailwindCSS  
[Repo](https://github.com/darischen/dchen)

---

## Backend

Building scalable APIs and services with focus on data infrastructure.

### gw-website-react
Full-stack Next.js application with serverless API routes (see Frontend section for details). Demonstrates backend architecture for e-commerce: order processing, payment webhook handling, inventory synchronization, and search infrastructure.

**Tech:** TypeScript, Next.js API Routes, Firebase, Supabase, Vercel  
[Repo](https://github.com/darischen/gw-website-react)

### PatentIQ
AI-powered patent search and drafting assistant for early-stage founders and inventors. Features semantic search via PostgreSQL pgvector embeddings over USPTO patent dataset, OAuth2 authentication via Auth0, and FastAPI backend with LLM integration for patent analysis and drafting suggestions.

**Tech:** TypeScript, Next.js, FastAPI (Python), PostgreSQL with pgvector, Auth0, OpenAI, Supabase, Vercel, EC2  
[Repo](https://github.com/darischen/PMA)

---

## DevOps

Infrastructure, deployment, and operational tooling.

Serverless-first deployment strategy using Vercel for frontend + API routes with automatic CI/CD. Experience with environment configuration, API integration pipelines, and webhook management. Infrastructure spans Vercel serverless, EC2 compute, and managed databases (PostgreSQL, Firebase).

**Tech:** Vercel, Next.js serverless, PostgreSQL, Supabase, EC2, GitHub Actions  

---

## Research

Novel systems and reproductions of cutting-edge research.

### HB100 Phased Array Radar
4-element HB100 Doppler radar array (10.525 GHz) with ESP32-S3 data acquisition and Raspberry Pi 4 signal processing. Implements MUSIC algorithm for angle-of-arrival estimation and Extended Kalman Filter for real-time target tracking. Computes target velocity, position, and movement trajectories. **First phased array implementation using HB100 microwave Doppler sensors.**

**Tech:** C, Python, Signal Processing (FFT, Butterworth filtering), Kalman filtering  
[Repo](https://github.com/darischen/PhasedArrayRadar)

### FishSense (UCSD Engineers for Exploration)
Custom R-CNN training pipeline (ResNet-50 backbone) for underwater laser-profiling research. Developed dual-laser photogrammetry algorithm to extract biological metrics (fish length/mass) from 2D video feeds, achieving sub-5% error rates in pixel-to-centimeter conversion. Standardized Detectron2 codebase, reducing inference setup time by 40% for new researchers.

**Tech:** Python, PyTorch, Detectron2, Computer Vision  

### RedShift
LLM jailbreaking research reproducing adversarial prompt engineering techniques. Features DeBERTa finetuning, adversarial attack generation, and benchmarking across language models (Vicuna, etc.) with Weights & Biases tracking.

**Tech:** Python, PyTorch, HuggingFace Transformers, DeBERTa  
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
