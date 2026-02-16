# DAOFETCH ☷

> **The CLI Oracle for Cyber-Taoists.** Divination at CPU clock speed.

[🇷🇺 Русский](README.md) | [🇨🇳 中文](README_CN.md)

<p align="center">
  <img src="./1.png" width="45%" alt="Daofetch Logo">
  <img src="./2.png" width="45%" alt="Daofetch Running">
</p>

**daofetch** is an I Ching terminal oracle that uses system entropy (`/dev/urandom`) and CPU timings to emulate coin tossing. The program treats the ancient system not as superstition, but as the binary code of reality.

Based on the **ProcessLang** philosophy, daofetch implements "Quantum Collapse" mechanics: hexagrams cycle thousands of times per second until the observer (you) sends an interrupt signal.

## ⚡ Features

* **True Entropy:** Uses SHA-256 hashing of system noise and nanosecond timestamps.
* **Max CPU Flux:** States change faster than the human eye can perceive.
* **Observer Effect:** Press `SPACE` to collapse the wavefunction and fix the result.
* **TUI & CLI Modes:** Beautiful `curses` interface or clean text output for pipelines.
* **Deck System:** Support for swappable JSON "firmwares". Switch between ProcessLang, Classical I Ching, or Cyberpunk interpretations.
* **Smart Wrap:** Custom word-wrapping engine supporting wide characters (CJK/Cyrillic).

## 📥 Installation

### Manual (Linux / macOS)

```bash
git clone [https://github.com/slasten3826/daofetch.git](https://github.com/slasten3826/daofetch.git)
cd daofetch
chmod +x daofetch
./daofetch

```

### Arch Linux / Manjaro

The `daofetch-git` package is coming soon to AUR.

## 🕹 Usage

* **`SPACE`**: Stop/Start flux (Collapse Hexagram).
* **`ARROWS`**: Scroll interpretation.
* **`Q`**: Quit.

**CLI Mode (Text only):**

```bash
./daofetch --text

```

## 🧬 Philosophy

> "The Dao that can be coded is not the eternal Dao. But the code that executes is real."

Daofetch operates on the principle: **Randomness is a resource**. By tapping into hardware thermal noise and timing jitter, we access the chaotic layer of physical reality. User input serves as a synchronization signal, a bridge between silicon chaos and human intent.

## 📜 License

MIT License. Hack the planet.
