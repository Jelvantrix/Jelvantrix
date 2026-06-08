<div align="center">

```
    ██╗███████╗██╗    ██╗   ██╗ █████╗ ███╗   ██╗████████╗██████╗  █████╗ ██╗  ██╗
    ██║██╔════╝██║    ██║   ██║██╔══██╗████╗  ██║╚══██╔══╝██╔══██╗██╔══██╗╚██╗██╔╝
    ██║█████╗  ██║    ██║   ██║███████║██╔██╗ ██║   ██║   ██████╔╝███████║ ╚███╔╝ 
██   ██║██╔══╝  ██║    ╚██╗ ██╔╝██╔══██║██║╚██╗██║   ██║   ██╔══██╗██╔══██║ ██╔██╗ 
╚█████╔╝███████╗███████╗╚████╔╝ ██║  ██║██║ ╚████║   ██║   ██║  ██║██║  ██║██╔╝ ██╗
 ╚════╝ ╚══════╝╚══════╝ ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

**Founder, Xynlvantrex Labs**

*We research, experiment, and build things that don't exist yet. Then we ship them.*

</div>

---

## Xynlvantrex Labs

I run **Xynlvantrex Labs** — an independent research and engineering lab focused on building things that have no prior art. Not products that improve on what exists. Things that don't exist at all.

The process is simple: identify a problem nobody has solved the right way, research it from first principles, experiment until something works, then deploy it.

I'm young. I don't have a degree or years of industry experience. What I have is the ability to build anything I decide to build — across systems, AI, security, compilers, networking, and beyond — and the discipline to see it through.

The lab is early. The work is real.

---

## Projects

---

### HELIX — Transformer Inference Engine
> `Rust` `Systems` `AI Infrastructure` `gRPC`

A production-grade GPT-2 inference engine written entirely in Rust. No PyTorch. No ML frameworks. Every component hand-rolled — because understanding a system means building it yourself.

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
117M params · 41 tok/s · 68% FLOP utilization · 38ms TTFT
```

**→ [github.com/Jelvantrix/HELIX](https://github.com/Jelvantrix/HELIX)** `In Progress` `Open to Contributions`

---

### EREBUS-KRONOS — Custom OS + Compiler Stack
> `Rust` `C` `OS Development` `Compilers`

An experimental computing stack built entirely from scratch. Not a hobby bootloader — an actual working system with a kernel, desktop, compiler, and custom programming language.

- Custom 32-bit kernel and bootloader
- Handwritten filesystem
- Desktop environment with working GUI (booted in VirtualBox)
- Custom programming language (Kronos) compiled with a Rust-written compiler
- Networking stack, audio subsystem, package manager

Everything from the first bootloader instruction to the window manager is original code.

**→ [github.com/Jelvantrix/Erebus-Kronos](https://github.com/Jelvantrix/Erebus-Kronos)**

---

### SENTINEL — Cyber Defense Operating Environment
> `Rust` `TypeScript` `Tauri` `eBPF` `Security`

A modular, offline-sovereign, zero-cloud cyber defense platform. 46 Rust crates. 12 architectural layers. 464 tests. Built in approximately one day.

- eBPF kernel-level process tracing
- Memory forensics engine
- Malware sandboxing with YARA integration
- Autonomous threat response
- Honeypot infrastructure
- Fully air-gap capable — no external cloud dependency

**→ [github.com/Jelvantrix/SENTINEL](https://github.com/Jelvantrix/SENTINEL)**

---

### AI Desktop Operator — Autonomous PC Control
> `AI` `Python` `Agents` `Computer Vision`

An autonomous agent that controls an entire PC through natural language. No APIs. No overlays. Direct system control across the full desktop environment.

**→ [github.com/Jelvantrix/AI-Desktop-Operator](https://github.com/Jelvantrix/AI-Desktop-Operator)** `In Progress`

---

## Stack

```
Languages     Rust · TypeScript · Python · C · Go
Systems       Linux kernel · eBPF · memory management · OS development
AI/ML         transformer architecture · inference engines · autonomous agents
Security      threat detection · memory forensics · sandboxing · YARA
Networking    custom protocol stacks · gRPC · WebSockets
Tooling       Cargo · Tokio · Tauri · axum · tonic
Environment   Arch Linux · KDE Plasma
```

---

## How I Work

I don't use abstractions I don't understand.

Before using any foundational library, I build the thing myself first — not to reinvent wheels, but to know exactly what the wheel is made of. Every project here started with a blank file.

I work across domains because systems talk to each other. An inference engine needs a tensor core. A tensor core needs memory management. Memory management needs to know the hardware. You can't draw a clean border between disciplines and still build something serious.

I'm young, self-taught, and independent. Xynlvantrex Labs is where I do my most ambitious work — things that don't exist yet, built the way they should be built.

---

<div align="center">

*Not open to work. Building the lab.*

**[Xynlvantrex Labs](https://github.com/Jelvantrix)** · Founded by Jelvantrix

</div>
