<p align="center"><img width="384" src="https://github.com/xodus-gaming/xodus/blob/main/assets/FullText/FullText452.png?raw=true" /></p>

> **Bringing Xbox PC games to Linux and macOS.**

Xodus is an open-source reverse-engineering effort to make Xbox PC games (including GamePass) run on Linux and Mac systems. We handle everything needed to get GDK-based Xbox titles running outside of Windows.

This project is not affiliated nor endorsed by Microsoft. Use at your own risk.

## 📦 Repositories

### [xodus](https://github.com/xodus-gaming/xodus)
The core project - written in Rust. Handles the full pipeline from Xbox authentication, token exchange through to package downloading and decryption.

### [ntfs](https://github.com/xodus-gaming/ntfs)
A fork of [ColinFinck/ntfs](https://github.com/ColinFinck/ntfs), adapted to support MSIXVC container parsing requirements.

### [xgameruntime-docs](https://github.com/xodus-gaming/xgameruntime-docs)
Reverse-engineering documentation for `xgameruntime.dll` internals - a key component of the Xbox PC runtime that games depend on.

### [wine](https://github.com/xodus-gaming/wine)
A fork of Proton's wine with additional patches enabling integration with Xodus and support for starting executables from memfd files.

### [xal-rs](https://github.com/xodus-gaming/xal-rs)
A fork of [OpenXbox/xal-rs](https://github.com/OpenXbox/xal-rs), extended with additional structs, fields and auth utils.

## 🤝 Get Involved

- Join the conversation on **[Discord](https://discord.gg/ZG774FK4tq)**
- Check out open **[issues](https://github.com/xodus-gaming/xodus/issues)** and **[pull requests](https://github.com/xodus-gaming/xodus/pulls)**
- Browse the code and documentation across our repos above

---

*Licensed under GPL-3.0*
