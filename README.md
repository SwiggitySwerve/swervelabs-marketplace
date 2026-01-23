# SwerveLabs Marketplace

AI-powered development tools and skills for OpenCode and Claude Code.

## Installation

### For Claude Code

```bash
/plugin marketplace add swiggityswerve/swervelabs-marketplace
```

### For OpenCode

Add plugins directly to your `opencode.json`:

```json
{
"plugin": ["locus-product-planning"]
}
```

---

## Available Plugins

### Locus Product Planning

**AI-powered product planning: Vision → Features → Design → Build**

Guide your products from idea to implementation through a simple 4-step process. No complicated commands - just describe what you want to build.

| | |
|---|---|
| **Version** | 1.2.17 |
| **Commands** | `/locus`, `/locus-status`, `/locus-list` |
| **npm** | `locus-product-planning` |
| **Repository** | [github.com/SwiggitySwerve/locus-product-planning](https://github.com/SwiggitySwerve/locus-product-planning) |

**Install (Claude Code):**
```bash
/plugin install locus-product-planning@swervelabs-marketplace
```

**Install (OpenCode):**
```json
{"plugin": ["locus-product-planning"]}
```

**Quick Start:**
```
You: I want to build an AI trading simulator

Locus: I'll help you plan and build this step by step.

       📋 AI Trading Simulator
       ━━━━━━━━━━━━━━━━━━━━━━━
       → Step 1: Vision ◄
         Step 2: Features
         Step 3: Design
         Step 4: Build

       What problem does this solve?
```

Say **"continue"** to move forward. That's it.

---

### UX Toolkit

**AI-powered UI/UX review toolkit with 25 skills and 18 agents**

Comprehensive toolkit for usability audits, accessibility compliance (WCAG 2.2), visual design analysis, interaction pattern review, and specialized page reviews (list, detail, editor, game UI, replay).

| | |
|---|---|
| **Version** | 0.5.2 |
| **Commands** | `/ux-audit`, `/a11y-check`, `/design-review`, `/screenshot-review` |
| **Agents** | 18 specialized agents for UX, accessibility, visual design, and interaction review |
| **Skills** | 25 skills covering heuristics, WCAG, visual systems, patterns, and more |
| **npm** | `ux-toolkit` |
| **Repository** | [github.com/SwiggitySwerve/ux-toolkit](https://github.com/SwiggitySwerve/ux-toolkit) |

**Install (Claude Code):**
```bash
/plugin install ux-toolkit@swervelabs-marketplace
```

**Install (OpenCode):**
```json
{"plugin": ["ux-toolkit"]}
```

**Or install globally via CLI:**
```bash
npx ux-toolkit install --global
```

**Quick Start:**
```
/ux-audit src/components/Button.tsx

→ Performs comprehensive UX audit against Nielsen's heuristics
→ Checks WCAG 2.2 accessibility compliance
→ Reviews visual design consistency
→ Provides severity-rated issues with specific fixes
```

---

## Marketplace Structure

```
swervelabs-marketplace/
├── .claude-plugin/
│   └── marketplace.json    # Plugin catalog
├── opencode.json           # OpenCode CLI configuration
├── README.md               # This file
└── LICENSE                 # MIT
```

## Support

- **Issues**: [github.com/SwiggitySwerve/swervelabs-marketplace/issues](https://github.com/SwiggitySwerve/swervelabs-marketplace/issues)
- **Locus Product Planning**: [github.com/SwiggitySwerve/locus-product-planning](https://github.com/SwiggitySwerve/locus-product-planning)
- **UX Toolkit**: [github.com/SwiggitySwerve/ux-toolkit](https://github.com/SwiggitySwerve/ux-toolkit)

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
