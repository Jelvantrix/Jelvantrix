<div align="center">

```
 ██╗███████╗██╗     ██╗   ██╗ █████╗ ███╗   ██╗████████╗██████╗ ██╗██╗  ██╗
 ██║██╔════╝██║     ██║   ██║██╔══██╗████╗  ██║╚══██╔══╝██╔══██╗██║╚██╗██╔╝
 ██║█████╗  ██║     ██║   ██║███████║██╔██╗ ██║   ██║   ██████╔╝██║ ╚███╔╝ 
 ██║██╔══╝  ██║     ╚██╗ ██╔╝██╔══██║██║╚██╗██║   ██║   ██╔══██╗██║ ██╔██╗ 
 ██║███████╗███████╗ ╚████╔╝ ██║  ██║██║ ╚████║   ██║   ██║  ██║██║██╔╝ ██╗
 ╚═╝╚══════╝╚══════╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝╚═╝╚═╝  ╚═╝
```

**I build systems from scratch. No frameworks as crutches. No shortcuts.**

</div>

---

I'm an independent systems engineer and multi-domain builder. I work at the intersection of low-level systems, AI infrastructure, and security — designing things most people reach for a library to solve.

Everything I build, I understand at the byte level.

---

## Projects

---

### HELIX — Transformer Inference Engine
> `Rust` `Systems` `AI Infrastructure` `gRPC`

A production-grade GPT-2 inference engine written entirely in Rust. No PyTorch. No ML frameworks. Every component hand-rolled.

- Custom tensor engine with AVX2/FMA SIMD acceleration
- BPE tokenizer loaded directly from OpenAI's vocab files
- KV-cache with O(1) fork for beam search
- 7 sampling strategies including Mirostat v2
- Zero-copy safetensors loader via memory-mapped files
- GGUF dequantization (Q8_0, Q4_K)
- gRPC streaming API + OpenAI-compatible REST
- Built-in profiler with Chrome trace export
- FLOP utilization benchmarking against theoretical peak

```
117M params | 41 tok/s | 68% FLOP utilization | 38ms TTFT
```

**→ [github.com/Jelvantrix/HELIX](https://github.com/Jelvantrix/HELIX)** `[In Progress]` `[Open to Contributions]`

---

### EREBUS-KRONOS — Custom OS + Compiler Stack
> `Rust` `C` `Systems` `Compilers` `OS Development`

An experimental computing stack built entirely from scratch. Not a hobby bootloader. An actual working system.

- Custom 32-bit kernel and bootloader
- Handwritten filesystem
- Desktop environment with working GUI
- Custom programming language (Kronos) with its own Rust-compiled compiler
- Networking stack and audio subsystem
- Package manager
- Successfully booted in VirtualBox with a working GUI

The entire stack — from the first instruction in the bootloader to the window manager — is original code.

**→ [github.com/Jelvantrix/Erebus-Kronos](https://github.com/Jelvantrix/Erebus-Kronos)**

---

### SENTINEL — Cyber Defense Operating Environment
> `Rust` `TypeScript` `Tauri` `eBPF` `Security`

A modular, offline-sovereign cyber defense platform. 46 Rust crates. 12 architectural layers. 464 tests.

- eBPF kernel-level process tracing
- Memory forensics engine
- Malware sandboxing with YARA integration
- Autonomous threat response system
- Honeypot infrastructure
- Zero external cloud dependency — fully air-gap capable
- Built in approximately one day

**→ [github.com/Jelvantrix/SENTINEL](https://github.com/Jelvantrix/SENTINEL)**

---

### AI Desktop Operator — Autonomous PC Control
> `AI` `Python` `Computer Vision` `Agents`

An autonomous agent that controls an entire PC through natural language. No APIs. No screen overlays. Direct computer control.

- Natural language → system actions
- Full desktop environment control
- Terminal access, file management, app control
- Multi-platform

**→ [github.com/Jelvantrix/AI-Desktop-Operator](https://github.com/Jelvantrix/AI-Desktop-Operator)** `[In Progress]`

---

## Stack

```
Languages     Rust · TypeScript · Python · C · Go
Systems       Linux · eBPF · memory management · kernel development
AI/ML         transformer architecture · inference engines · autonomous agents
Security      threat detection · memory forensics · sandboxing · YARA
Networking    custom stacks · gRPC · WebSockets · Tor
Tooling       Cargo · Tokio · Tauri · axum · tonic
OS            Arch Linux · KDE Plasma
```

---

## How I Work

I don't reach for abstractions I don't understand.

Before using a library for anything foundational, I build it myself first — not to reinvent the wheel, but to understand what the wheel actually is. Every project here started with a blank file and grew from first principles.

I work alone, autonomously, and ship things that work.

---

<div align="center">

*Not open to work. Just building.*

**[github.com/Jelvantrix](https://github.com/Jelvantrix)**

</div>
