<div align="center">

<img src="https://static.wikia.nocookie.net/pokemon/images/4/49/Ash_Pikachu.png/revision/latest/scale-to-width-down/1000?cb=20200405125039" alt="Pikachu" width="200"/>

# ⚡ pikachu-mode

**Your AI coding assistant, but it speaks Pikachu.**

[![Made with Love](https://img.shields.io/badge/Made%20with-⚡Pika⚡-yellow?style=flat-square)](https://github.com/mapoallegro/pikachu-mode)
[![Token Savings](https://img.shields.io/badge/Token%20Savings-15--40%25-green?style=flat-square)](#-token-savings)
[![Fun Factor](https://img.shields.io/badge/Fun%20Factor-Over%209000-red?style=flat-square)](#-intensity-levels)

*A communication mode plugin for Copilot CLI & Claude Code that replaces filler, pleasantries, and hedging with Pikachu vocabulary — while keeping **full technical accuracy**.*

</div>

---

## Why?

Every time your AI says *"Sure! I'd be happy to help you with that. The issue you're experiencing is likely caused by..."* — that's **42 wasted tokens** before any useful content.

**pikachu-mode** kills the filler. What you get instead:

```
Pika-pika! Spring can't find adapter for your port. 
Pi-ka, check `@Component` on adapter class implementing the port interface. Chu!
```

Same info. Less fluff. More ⚡.

## 💰 Token Savings

Standard AI responses waste **30-50 tokens per reply** on pleasantries alone ("Sure! I'd be happy to help you with that..."). Over a long coding session, that's thousands of tokens doing nothing.

| Level | Estimated Savings | How |
|-------|-------------------|-----|
| **lite** | ~15% | Removes pleasantries, hedging, filler phrases |
| **full** | ~25% | + replaces transitions with short Pika-words |
| **ultra** | ~35% | + fragments, maximum compression with Pika flavor |
| **pokemon** | ~40% | All prose → Pika vocabulary, code carries meaning |

> **Note:** pikachu-mode prioritizes **readability and fun** alongside savings. Code blocks — where the real value lives — stay 100% intact. You get shorter responses that are more enjoyable to read.

## 🎮 Intensity Levels

### `lite` — Professional with Pika flavor
> "Pika! Your port interface isn't being injected because Spring can't find the adapter implementation. Make sure your adapter class is annotated with `@Component`. Pikachu!"

### `full` — Classic Pikachu engineer *(default)*
> "Pika-pika! Spring can't find adapter for your port. Pi-ka, check `@Component` on adapter class implementing the port interface. Chu!"

### `ultra` — Maximum Pika saturation
> "PIKAA! Port has no adapter bean pika! `@Component` on adapter impl class chu chu! Pikachu!"

### `pokemon` — Pure Pikachu + code blocks
> Pi...ka...chu... 😟
> 
> ```kotlin
> // PIKAA!
> class OrderAdapter : OrderPort  // pi pika chu...
> 
> // PIKACHU! ✓
> @Component
> class OrderAdapter : OrderPort
> ```
> 
> Pika pika pi! ⚡

### `pokemon` — without code (conceptual answer)

*Question: "What's the difference between input and output ports?"*

> Pika-pika! ⚡
>
> **Input port** 👆 ← pika pika! (outside → domain)
>
> **Output port** 👇 ← chu chu! (domain → outside)
>
> Pika-pi: input = "pika?" (what can you do for me?)
>
> Chu: output = "pikachu!" (what do you need from others?)
>
> ⚡ Pika pika pi!

## 🚀 Quick Start

### Install

Add the plugin to your agent configuration:

**Copilot CLI / Claude Code** — add to `.claude/settings.json`:
```json
{
  "plugins": [
    "/path/to/pikachu-mode"
  ]
}
```

### Usage

| Command | Effect |
|---------|--------|
| "pikachu mode" | Activate (default: full) |
| `/pikachu lite` | Switch to lite |
| `/pikachu full` | Switch to full |
| `/pikachu ultra` | Switch to ultra |
| `/pikachu pokemon` | Switch to pokemon |
| "stop pikachu" | Deactivate |
| "normal mode" | Deactivate |

## 🧠 How It Works

pikachu-mode defines a **vocabulary mapping** where Pikachu words replace specific categories of filler:

| Pika-word | Replaces | Mood |
|-----------|----------|------|
| `Pika!` | sure/ok/yes | ✅ Affirmation |
| `Pikachu!` | done/success/great | 🎉 Completion |
| `Pika-pi` | note/important | ⚠️ Attention |
| `Chuuu...` | hmm/thinking | 🤔 Uncertainty |
| `PIKAA!` | error!/danger! | 🔥 Critical |
| `Pi-ka` | next/then/so | ➡️ Transition |
| `Pika-pika` | let me explain | 💡 Explanation |

**What stays untouched:**
- ✅ Code blocks
- ✅ Technical terms
- ✅ Error messages
- ✅ File paths & commands
- ✅ API names & class names

## 🔒 Safety: Auto-Clarity

Pikachu mode **automatically disengages** for:
- 🛡️ Security warnings
- ⚠️ Irreversible action confirmations  
- 📋 Complex multi-step instructions where Pika-words could confuse order

Full, clear human language returns for critical moments. Pikachu resumes after.

## 🎯 Designed For

- **Any developer** — works with every language and framework
- **Teams who want lighter AI interactions** without losing substance
- **Long coding sessions** where token savings add up
- **Anyone who thinks their terminal needs more ⚡**

## 📄 License

MIT — Pika pika pi!

---

<div align="center">

*"Pikachu, I choose you!"* — every developer activating this plugin

**⚡ Pika!**

</div>
