# Edge Model Zoo

<details>
  <strong>Date</strong>: 12-04-2025  | <strong>Version</strong>: 1.1
</details>

[![Hits](https://hits.sh/github.com/Jewelzufo/ollama-models.svg?style=for-the-badge&label=Repo%20Views&color=0D1117&labelColor=1F6FEB&logo=github)](https://github.com/Jewelzufo/ollama-models)

---

The following models were optimized for use on edge devices. Each model listed has been tested on a Raspberry Pi 5 (8gb) device. 

## Granite-4.0-H-350M-GGUF

![Unsloth Granite 4.0 H 350M GGUF](https://ollama.com/assets/jewelzufo/unsloth_granite-4.0-h-350m-GGUF/fa683f7c-4665-45e6-addd-c3629f393798)

>**Quantized models** *(160-685mb)*
>>https://ollama.com/jewelzufo/unsloth_granite-4.0-h-350m-GGUF

**Use cases:**
- Pocket-sized enterprise assistant
- Local RAG for docs and tickets
- Function-calling agent for lightweight workflows

---


## Vertalily-1.2-1B

>**Description:** In comparative evaluation, Verta Lily‑1.2‑1B achieved superior performance in general knowledge (78 % ± 3) and oracle reasoning (74 % ± 4), surpassing larger baselines such as Gemma-4-E2B (google/gemma-4-E2B), Qwen3‑4B (Qwen/Qwen3-4B), and Microsoft Phi‑3‑mini (microsoft/Phi-3-mini-4k-instruct), as well as the compact LFM2.5‑1.2B‑Instruct (LiquidAI/LFM2.5-1.2B-Instruct), with statistically significant margins (p < 0.05). Its compact 1 B architecture consistently delivered higher factual recall and logical coherence while maintaining quantization stability, translating into a normalized performance‑per‑cost score of 1.20 — the highest among all tested systems. This establishes Verta Lily as a benchmark‑efficient model, providing 20 % more usable reasoning per compute unit compared to peers.

- **Ollama Download:** (https://ollama.com/jewelzufo/VertaLily-1.2-1B:latest)

>**Size** *(600mb)*
>**Quantization:** *Q4_K_M*

**Use cases:**
- On-device general-knowledge assistant
- Cost-efficient reasoning API
- Local RAG with private docs

<br>

---

## MiniCPM5-1B

### Description 

🏆 **1B-class open-source SOTA**: compared with strong open-source models in the same size class, MiniCPM5-1B reaches SOTA within this comparison set. Its advantage is most visible in agentic tool use, code generation, and difficult reasoning.

![MiniCPM5 logo](https://raw.githubusercontent.com/OpenBMB/MiniCPM/main/assets/minicpm_logo.png)

**Download:** [Ollama Download](https://ollama.com/jewelzufo/MiniCPM5-1B)

>**Size** *(688mb)*
>**Quantization:** *Q4_K_M*

**Use Cases:**
- On-device personal assistants
- Coding Agents
- Agentic Tool Use Workflows
- Hybrid Reasoning
- Long context tasks (131k context window)

---

<br>