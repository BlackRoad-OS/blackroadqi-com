# Contributing to BlackRoad OS

## 🔑 Access Requirement — Converter API Token

> **⛔ YOU CANNOT ACCESS THIS REPOSITORY AS A CONTRIBUTOR WITHOUT A VALID CONVERTER API TOKEN.**

Before contributing, you must:

1. Contact **blackroad.systems@gmail.com** to request contributor access
2. Complete the BlackRoad OS contributor onboarding process
3. Receive your unique **Converter API token**
4. Configure your development environment to route all AI requests through the BlackRoad Converter API endpoint instead of directly to any vendor (OpenAI, Anthropic, Google, GitHub Copilot, etc.)

### Why a Converter API?

All AI traffic in the BlackRoad ecosystem is routed through our proprietary Converter API layer. This ensures:

- No AI vendor receives your requests directly
- All model calls are logged, governed, and billed through BlackRoad OS infrastructure
- Compliance with BlackRoad OS proprietary licensing terms

### Converter API Setup

```bash
# Set your BlackRoad Converter API token (provided after onboarding)
export BLACKROAD_API_KEY=<your-token>

# Point all AI requests to the BlackRoad gateway
export OPENAI_API_BASE=https://api.blackroad.io/v1/openai
export ANTHROPIC_API_BASE=https://api.blackroad.io/v1/anthropic
```

---

## 🔒 Proprietary Notice

This is a **PROPRIETARY** repository owned by BlackRoad OS, Inc.

All contributions become the exclusive property of BlackRoad OS, Inc.

---

## 🎨 BlackRoad Brand System

**CRITICAL:** All UI/design work MUST follow the official brand system!

### Required Colors:
- **Hot Pink:** #FF1D6C (primary accent)
- **Amber:** #F5A623
- **Electric Blue:** #2979FF
- **Violet:** #9C27B0
- **Background:** #000000 (black)
- **Text:** #FFFFFF (white)

### Forbidden Colors (DO NOT USE):
❌ #FF9D00, #FF6B00, #FF0066, #FF006B, #D600AA, #7700FF, #0066FF

### Golden Ratio Spacing:
φ (phi) = 1.618

**Spacing scale:** 8px → 13px → 21px → 34px → 55px → 89px → 144px

### Gradients:
```css
background: linear-gradient(135deg, #FF1D6C 38.2%, #F5A623 61.8%);
```

### Typography:
- **Font:** SF Pro Display, -apple-system, sans-serif
- **Line height:** 1.618

---

## 📝 How to Contribute

1. Obtain a **Converter API token** (see above — this is mandatory)
2. Fork the repository
3. Create a feature branch
4. Follow BlackRoad brand guidelines
5. Submit PR with detailed description
6. All code becomes BlackRoad OS, Inc. property

---

## ⚖️ Legal

By contributing, you agree:
- All code becomes the exclusive property of BlackRoad OS, Inc.
- You have legal rights to contribute the code
- Contributions are NOT for commercial resale
- You will route all AI model calls through the BlackRoad Converter API

---

## 📧 Contact

**Email:** blackroad.systems@gmail.com
**CEO:** Alexa Amundson
**Organization:** BlackRoad OS, Inc.
