# Xodus

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

## 🎮 What games are supported?

Xodus targets games distributed in **GDK + MSIXVC format**. Support for the broader Xbox PC catalog is the goal. Some titles (e.g. *Gears of War 4*) remain unsupported for now due to format differences.

Full Wine/Proton-level Xbox Services support is still being developed, so end-to-end gameplay isn't available yet - but the project is maturing quickly.


## 🤝 Get Involved

- Join the conversation on **[Discord](https://discord.gg/ZG774FK4tq)**
- Check out open **[issues](https://github.com/xodus-gaming/xodus/issues)** and **[pull requests](https://github.com/xodus-gaming/xodus/pulls)**
- Browse the code and documentation across our repos above

---

*Licensed under GPL-3.0*
