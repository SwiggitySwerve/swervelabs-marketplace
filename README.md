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
  "plugin": ["opencode-locus"]
}
```

---

## Available Plugins

### Locus

**AI-powered project planning: Vision → Features → Design → Build**

Guide your projects from idea to implementation through a simple 4-step process. No complicated commands - just describe what you want to build.

| | |
|---|---|
| **Commands** | `/locus`, `/locus-status`, `/locus-list` |
| **npm** | `opencode-locus` |
| **Repository** | [github.com/SwiggitySwerve/locus](https://github.com/SwiggitySwerve/locus) |

**Install (Claude Code):**
```bash
/plugin install locus@swervelabs-marketplace
```

**Install (OpenCode):**
```json
{"plugin": ["opencode-locus"]}
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

## Marketplace Structure

```
swervelabs-marketplace/
├── .claude-plugin/
│   └── marketplace.json    # Plugin catalog
├── README.md               # This file
└── LICENSE                 # MIT
```

## Support

- **Issues**: [github.com/SwiggitySwerve/swervelabs-marketplace/issues](https://github.com/SwiggitySwerve/swervelabs-marketplace/issues)
- **Locus Plugin**: [github.com/SwiggitySwerve/locus](https://github.com/SwiggitySwerve/locus)

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
