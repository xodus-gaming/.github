<p align="center"><img width="384" src="https://github.com/xodus-gaming/xodus/blob/main/assets/FullText/FullText452.png?raw=true" /></p>

> **Bringing Xbox PC games to Linux and macOS.**

Xodus is an open-source reverse-engineering effort to make Xbox PC games (including GamePass) run on Linux and Mac systems. We handle everything needed to get GDK-based Xbox titles running outside of Windows.

This project is not affiliated nor endorsed by Microsoft. Use at your own risk.

## 📦 Repositories

| Repo | Description |
|---|---|
| [xodus](https://github.com/xodus-gaming/xodus) | Core project (Rust) - auth, token exchange, package download and license acquisition. |
| [xgameruntime](https://github.com/xodus-gaming/xgameruntime) | Implementation of `xgameruntime.dll`, the Xbox PC runtime component games depend on. |
| [xgameruntime-docs](https://github.com/xodus-gaming/xgameruntime-docs) | Clean-room reverse-engineering docs for `xgameruntime.dll` internals. |
| [xal-rs](https://github.com/xodus-gaming/xal-rs) | Fork of [OpenXbox/xal-rs](https://github.com/OpenXbox/xal-rs) - Xbox auth library for Windows-style SISU auth. |
| [ntfs](https://github.com/xodus-gaming/ntfs) | Fork of [ColinFinck/ntfs](https://github.com/ColinFinck/ntfs), adapted for MSIXVC container parsing. |
| [wine](https://github.com/xodus-gaming/wine) | Fork of [ValveSoftware/wine](https://github.com/ValveSoftware/wine) with patches for Xodus integration. |
| [Proton](https://github.com/xodus-gaming/Proton) | Fork of [ValveSoftware/Proton](https://github.com/ValveSoftware/Proton) bundling the Xodus-patched Wine. |

## 🤝 Get Involved

- Join the conversation on **[Discord](https://discord.gg/ZG774FK4tq)**
- Check out open **[issues](https://github.com/xodus-gaming/xodus/issues)** and **[pull requests](https://github.com/xodus-gaming/xodus/pulls)**
- Browse the code and documentation across our repos above
