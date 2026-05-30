## Dari Chen

CS student at UC San Diego. I build things at the intersection of signal processing, computer vision, and embedded systems — mostly in Python, C, and SystemVerilog, with TypeScript for anything that needs a UI.

Currently targeting research and applied ML roles focused on real-time inference, sensor fusion, and hardware-software co-design.

---

### Projects

**[HandVol](https://github.com/darischen/HandVol)** — gesture-controlled Windows volume and media via webcam.
Runs MediaPipe's pretrained gesture recognizer with custom landmark-based detection layered on top for gestures the classifier doesn't cover (OK sign, sideways thumb, shaka). No model training, no cloud calls, local inference only. Includes a faster-whisper voice search pipeline and a face identity module using cosine similarity on landmark embeddings.

**[PhasedArrayRadar](https://github.com/darischen/PhasedArrayRadar)** — 4-element HB100 Doppler radar array.
ESP32-S3 collects ADC samples from four 10.525 GHz modules over USB-CDC; Raspberry Pi 4 does the DSP: Butterworth bandpass, Hanning-windowed FFT, MUSIC algorithm for angle of arrival (with spatial smoothing and forward-backward averaging), and an Extended Kalman Filter tracking state (x, y, vx, vy).

**[Mini-Stockfish](https://github.com/darischen/Mini-Stockfish)** — chess engine with NNUE evaluation.
Bitboard representation, alpha-beta minimax with iterative deepening and quiescence search, transposition tables with MVV-LVA move ordering, and a neural network evaluator trained on 16 million Stockfish-evaluated positions.

**[EEWS](https://github.com/darischen/EEWS)** — earthquake early warning system.
ML-based seismic analysis pipeline in Jupyter, using signal features from raw waveforms for event detection and classification.

**[8bitCPU](https://github.com/darischen/8bitCPU)** — 8-bit processor in SystemVerilog.
9-bit instruction format, 4-register ISA, 256-byte data memory. Includes a Python assembler and three test programs: Hamming code, and two signed integer multiply routines.

**[dchen](https://github.com/darischen/dchen)** — personal site.
Built in Next.js, shows current work and contact info.

---

### Currently building

- **HandVol** — face identity gating (block gestures unless the enrolled user is in frame)
- **dchen** — portfolio site refresh

---

### Contact

UC San Diego · San Diego, CA
[github.com/darischen](https://github.com/darischen)
