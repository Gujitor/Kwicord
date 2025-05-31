# Kwicord by Gujitor  
*GitHub 2025 - 2026*

---

## What is Kwicord?

**Kwicord** is a unique P2P application combining the features of:  
- **Discord** (chat, voice calls, communities),  
- **Torrent** (direct peer-to-peer file sharing),  
- **RadminVPN** (secure VPN with encryption and local data storage).

Kwicord is designed to give users **freedom of communication without censorship or blocking** — your digital world that cannot be shut down.

---

## Architecture & Versions

Kwicord consists of several interconnected versions:

- **v0** — The Core of Kwicord, the foundation for all versions, written in Rust, C, and ASM.  
  - The Core runs inside a **sandbox**, isolated from the user system.  
  - It interacts with the user system and versions v1 to v3 through the **v0 Core API**.

### Core API (v0) main functions:
1. Connecting users via **WireGuard** (peer-to-peer connections).  
2. Data transmission of any format (video, audio, text, etc.).  
3. File sharing over P2P.  
4. Strong encryption and cryptography.

---

- **v1.n** — Built on top of the v0 Core.  
  - Fast-paced development, frequently adding new features and expanding the Core’s capabilities via API.

- **v2.n** — A stable build based on the v0 Core and the best features from v1.  
  - Rewritten and optimized code, slower but more stable updates.

- **v3** — The final commercial release of Kwicord.  
  - The most optimized and refined version, incorporating improvements from v2.

---

## Licenses

| Version | License                  |
|---------|--------------------------|
| v0, v1.n| MPL-2.0                  |
| v2.n    | AGPLv3                   |
| v3      | Commercial + Open Source Core |

---

## Why Kwicord?

> In an age of blocks and censorship, we need a tool that **cannot be silenced**.  
> Kwicord is **your voice and connection**, free from control and restrictions.

---

## Getting Started

*Coming soon — installation instructions for the v0 Core and how to connect v1–v3 versions.*

---
