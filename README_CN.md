# DAOFETCH (道 Fetch) ☷

> **赛博道士的命令行神谕。** 以 CPU 时钟速度进行占卜。

[🇷🇺 Русский](README.md) | [🇺🇸 English](README_EN.md)

<p align="center">
  <img src="./1.png" width="45%" alt="Daofetch Logo">
  <img src="./2.png" width="45%" alt="Daofetch Running">
</p>

**daofetch** 是一个终端易经（I Ching）工具，利用系统熵（`/dev/urandom`）和 CPU 计时来模拟掷币。该程序不将古老的系统视为迷信，而是将其视为现实的二进制代码。

基于 **ProcessLang** 哲学，daofetch 实现了“量子坍缩”机制：卦象每秒变化数千次，直到观察者（您）发出中断信号。

## ⚡ 特性

* **真实熵 (True Entropy):** 使用 SHA-256 对系统噪声和纳秒时间戳进行哈希处理。
* **CPU 极速流:** 状态变化速度超过人眼捕捉极限。
* **观察者效应:** 按下 `SPACE` 键以坍缩波函数并锁定结果。
* **TUI 和 CLI 模式:** 美观的 `curses` 界面或用于管道的纯文本输出。
* **卡组系统 (Decks):** 支持可替换的 JSON“固件”。在 ProcessLang、经典易经或赛博朋克解读之间切换。
* **智能换行:** 自定义换行引擎，完美支持宽字符（中文/西里尔字母）。

## 📥 安装

### 手动安装 (Linux / macOS)

```bash
git clone [https://github.com/slasten3826/daofetch.git](https://github.com/slasten3826/daofetch.git)
cd daofetch
chmod +x daofetch
./daofetch

```

### Arch Linux / Manjaro

`daofetch-git` 软件包即将登陆 AUR。

## 🕹 使用方法

* **`SPACE` (空格)**: 停止/开始 (卦象坍缩).
* **`方向键`**: 滚动解卦文本.
* **`Q`**: 退出.

**CLI 模式 (纯文本):**

```bash
./daofetch --text

```

## 🧬 哲学

> “道可道，非常道。但运行之码，即为真实。”

Daofetch 的运作原则是：**随机性是一种资源**。通过接入硬件热噪声和计时抖动，我们得以接触物理现实的混沌层。用户输入作为同步信号，架起了硅基混沌与人类意图之间的桥梁。

## 📜 许可证

MIT License. Hack the planet.
