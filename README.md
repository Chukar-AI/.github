<div align="center">
  <h1>Chukar AI</h1>
  <p><strong>Deterministic Local LLM Infrastructure & Anti-Cheat Evaluation</strong></p>
</div>

---

### Ecosystem

| Project | Stack | Purpose |
| :--- | :--- | :--- |
| **[VibeBench](https://github.com/Chukar-AI/vibe-bench)** | Python · Cloudflare D1 · Rust | Deterministic 18-pillar & anti-cheat evaluation suite for Dense & MoE local LLMs (`IQ1`–`Q8_0`). |
| **[Vibe Router](https://github.com/Chukar-AI/vibe-router)** | Rust | High-throughput local & hybrid LLM gateway with schema enforcement and intelligent routing. |
| **[Vibe Local](https://github.com/Chukar-AI/vibe-local)** | Rust · `llama.cpp` | Zero-bloat local inference runtime tuned for consumer GPUs and unified memory. |
| **[Vibe Assembly](https://github.com/Chukar-AI/vibe-assembly)** | Rust · Android / Desktop | Native agentic workspace with deterministic file patching (`FNV-1a`). |

---

### Engineering Principles
* **Measure the Cliff, Not Just the Peak:** Full quantization profiling down to `IQ1` and `Q2` to expose tool-suppression, syntax failures, and infinite `<think>` loops before deployment.
* **Zero-Contamination Verification:** Procedural state-machine tracing and private multi-constraint evaluations paired with deterministic code/AST graders.
* **Hardware-Aware Telemetry:** Real `PP/TG tok/s`, KV-Cache quantization impact, and VRAM budgets across `Dense` and `MoE` architectures.
