## Dari Chen

CS student at UC San Diego. Building across signal processing, computer vision, ML, and frontend — Python, C, TypeScript, SystemVerilog.

---

### AI/ML

*Inference pipelines and learned models.*

**[Mini-Stockfish](https://github.com/darischen/Mini-Stockfish)** — chess engine with NNUE evaluation.
Bitboard move generation, alpha-beta minimax with iterative deepening and quiescence search, transposition tables with MVV-LVA move ordering. Evaluator trained on 16 million Stockfish-annotated positions.

**[HandVol](https://github.com/darischen/HandVol)** — gesture-controlled Windows volume and media via webcam.
MediaPipe gesture classifier with custom landmark-based detection for uncovered gestures (OK sign, sideways thumb, shaka). Local inference only. Faster-whisper voice search pipeline and face identity module using cosine similarity on landmark embeddings.

---

### Research

*Sensor pipelines and hardware-software systems.*

**[PhasedArrayRadar](https://github.com/darischen/PhasedArrayRadar)** — 4-element HB100 Doppler radar array.
ESP32-S3 collects ADC samples from four 10.525 GHz modules over USB-CDC. Raspberry Pi 4 runs the DSP chain: Butterworth bandpass filter, Hanning-windowed FFT, MUSIC angle-of-arrival estimation with spatial smoothing and forward-backward averaging, Extended Kalman Filter tracking (x, y, vx, vy).

**[EEWS](https://github.com/darischen/EEWS)** — earthquake early warning system.
Seismic event detection and classification from raw waveforms. ML pipeline in Jupyter: signal features from accelerometer and seismometer channels for P-wave onset identification and magnitude estimation.

---

### Frontend

*Web UIs on Next.js and TypeScript.*

**[dchen](https://github.com/darischen/dchen)** — personal site. Next.js. Shows current work and contact.

**[weatherapp](https://github.com/darischen/weatherapp)** — location-aware weather app.
Next.js + PostgreSQL + Prisma + Zod + Tailwind. Integrates Open Meteo, Google Maps API, OSM Nominatim, Leaflet, and browser geolocation.

**[Simplerfy](https://github.com/darischen/Simplerfy)** — TypeScript.

**[FlipperZillow](https://github.com/darischen/FlipperZillow)** — TypeScript.

---

### Backend

*APIs, data pipelines, server-side tooling.*

**[career-ops](https://github.com/darischen/career-ops)** — job application pipeline automation. JavaScript.

**[FeatureRequest](https://github.com/darischen/FeatureRequest)** — feature request tracking. TypeScript.

---

### DevOps / Systems

*Embedded, HDL, and build tooling.*

**[8bitCPU](https://github.com/darischen/8bitCPU)** — 8-bit processor in SystemVerilog.
9-bit instruction format, 4-register ISA, 256-byte data memory. Python assembler included. Test programs: Hamming code encoder and two signed-integer multiply routines.

---

### Contact

UC San Diego · San Diego, CA
[github.com/darischen](https://github.com/darischen)
