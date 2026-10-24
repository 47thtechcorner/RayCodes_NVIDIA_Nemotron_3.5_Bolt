<div align="center">
  <a href="https://youtu.be/nFHkXVVup5Y">
    <img src="https://img.youtube.com/vi/nFHkXVVup5Y/0.jpg" alt="NVIDIA Nemotron 3.5 Bolt: This Tiny Desktop AI Agent Runs in 4GB! (Gemma 4 Upgrade)">
  </a>
  <h3>📺 <a href="https://youtu.be/nFHkXVVup5Y">Watch the full video on YouTube</a></h3>
</div>

# NVIDIA Nemotron 3.5 Bolt E4B (4GB)

[![License: OpenMDW-1.1](https://img.shields.io/badge/License-OpenMDW--1.1-blue.svg)](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Bolt-E4B-4GB)
[![Model Size: 8B / 4B Active](https://img.shields.io/badge/Model%20Size-8B%20Total%20%7C%204B%20Active-green.svg)](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Bolt-E4B-4GB)
[![Quantization: 2--Bit UD--IQ2__M](https://img.shields.io/badge/Quant-2--Bit%20UD--IQ2__M%20GGUF-purple.svg)](https://huggingface.co/unsloth/NVIDIA-Nemotron-3.5-Bolt-E4B-GGUF)
[![Local Footprint: 4GB VRAM](https://img.shields.io/badge/Hardware%20Req-4GB%20VRAM%20%7C%2016GB%20RAM-orange.svg)](https://research.nvidia.com/labs/nemotron/)

> *"Nemotron 3.5 Bolt E4B delivers high-speed, local multi-turn conversational agents with native asynchronous tool-calling, 64K context window, and configurable reasoning—fitting comfortably within 4GB VRAM on consumer setups."*

---

### Workflow Summary

| Task / Workflow | AI Superpower | Input Config | Expected Deliverable |
| :--- | :--- | :--- | :--- |
| **Local Desktop File Organizer** | 📂 Native Tool Execution & Safety | Authentic file directory with unorganized files (`inputs/_messy_desktop`) | Categorized folder tree + verification audit log (`outputs/_clean_desktop`) |
| **Daily Work Schedule Assistant** | ⏱️ Priority Reasoning & Buffer Planning | Unstructured task brief with hard deadlines (`inputs/daily_task_brief.md`) | Deconflicted chronological focus agenda (`outputs/daily_agenda`) |
| **Private Travel Expense Calculator** | 💰 Confidential On-Device Extraction | Raw unformatted receipt records (`inputs/raw_receipts/*.txt`) | Itemized expense ledger with sub-totals (`outputs/reconciled_ledger`) |

---

### Quick Start (Windows PowerShell)

```powershell
pip install requests rich

hf download unsloth/NVIDIA-Nemotron-3.5-Bolt-E4B-GGUF NVIDIA-Nemotron-3.5-Bolt-E4B-UD-IQ2_M.gguf --local-dir models

ollama create nemotron-3.5-bolt:2b-iq2 -f Modelfile
```

#### Run Pipeline

```powershell
python main.py
```

---

### Practical Use Cases

* 🎙️ **Zero-Delay Voice Desktop Assistant**: Run ultra-fast voice agents on consumer PCs that execute real local actions without freezing UI windows.
* 🛡️ **Private Document & File Triage**: Automate local folder cleanup and sensitive data organization completely offline with zero cloud risk.
* 🎮 **Immersion Game NPCs**: Power responsive, talking game characters that follow strict rules, remember quest histories, and run on local graphics cards.
* 💡 **Private Offline Smart Home Hub**: Coordinate IoT switches, temperatures, and security tools with speech-friendly conversational answers.

---

### Future Feature Roadmap

* 🚀 **DFlash Drafter Speculative Decoding**: Integrate speculative decoding via companion DFlash models for up to 21% faster token generation.
* 🎙️ **Local Real-Time Speech-to-Speech**: Pair with on-device speech models for zero-latency spoken two-way conversations.
* 🧩 **Dynamic Multi-Device IoT Connector**: Direct native integration into Home Assistant and local MQTT micro-controllers.
* 🌐 **Autonomous Browser Navigation Actions**: Add local web lookup tools without leaking user session tokens to third-party cloud servers.

---

### Search Keywords & Tags

`nemotron 3.5` `nemotron 3.5 bolt` `nvidia nemotron` `ollama nemotron` `nemotron bolt` `nemotron e4b` `gemma 4 nemotron` `offline ai assistant` `nemotron vs qwen` `nemotron vs gemma` `nemotron gguf` `private desktop agent` `nemotron tool calling` `nemotron benchmarks` `nvidia local ai` `NVIDIA Nemotron` `Nemotron 3.5` `Nemotron Bolt` `Nemotron E4B` `NVIDIA AI` `Nemotron 4GB` `Nemotron local` `Nemotron Ollama` `Gemma 4 E4B` `NVIDIA Gemma` `Gemma fine tuning` `Gemma vs Nemotron` `Gemma 4`
