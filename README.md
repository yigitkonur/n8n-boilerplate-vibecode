<h1 align="center">🔌 n8n Community Node Boilerplate 🔌</h1>
<h3 align="center">Stop wrestling with n8n docs. Start shipping nodes that work.</h3>

<p align="center">
  <strong>
    <em>The ultimate starter kit for building n8n community nodes with AI. Pre-configured rules for 11 coding assistants, 31 documentation files, and production-ready patterns — so your AI actually knows what the hell it's doing.</em>
  </strong>
</p>

<p align="center">
  <!-- Package Info -->
  <a href="https://docs.n8n.io/integrations/creating-nodes/"><img alt="n8n" src="https://img.shields.io/badge/n8n-Community%20Node-FF6D5A?style=flat-square&logo=n8n&logoColor=white"></a>
  <a href="https://www.typescriptlang.org/"><img alt="typescript" src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white"></a>
  <a href="https://nodejs.org/"><img alt="node" src="https://img.shields.io/badge/Node.js-22+-339933?style=flat-square&logo=node.js&logoColor=white"></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <!-- Features -->
  <a href="LICENSE.md"><img alt="license" src="https://img.shields.io/badge/License-MIT-F9A825?style=flat-square"></a>
  <a href="docs/"><img alt="docs" src="https://img.shields.io/badge/Docs-31%20Files-2ED573?style=flat-square"></a>
</p>

<p align="center">
  <img alt="11 tools" src="https://img.shields.io/badge/🤖_11_AI_tools-pre--configured_rules-2ED573.svg?style=for-the-badge">
  <img alt="production ready" src="https://img.shields.io/badge/📦_production_ready-working_examples_included-2ED573.svg?style=for-the-badge">
</p>

<div align="center">

### 🧭 Quick Navigation

[**⚡ Get Started**](#-get-started-in-90-seconds) •
[**✨ Key Features**](#-feature-breakdown-the-secret-sauce) •
[**🤖 AI Tool Setup**](#-ai-tool-configuration) •
[**📚 Documentation**](#-documentation-31-files) •
[**🆚 Why This Slaps**](#-why-this-slaps-other-methods)

</div>

---

**n8n Community Node Boilerplate** is the project manager your AI coding assistant wishes it had. Stop feeding your LLM random n8n docs and praying for working code. This repo acts like a senior n8n developer, providing structured rules, comprehensive documentation, and battle-tested patterns so your AI can actually build nodes that work the first time.

<div align="center">
<table>
<tr>
<td align="center">
<h3>🧠</h3>
<b>AI-Optimized Rules</b><br/>
<sub>11 tools pre-configured</sub>
</td>
<td align="center">
<h3>📚</h3>
<b>31 Doc Files</b><br/>
<sub>Every n8n pattern covered</sub>
</td>
<td align="center">
<h3>🏗️</h3>
<b>Working Examples</b><br/>
<sub>Copy, modify, ship</sub>
</td>
</tr>
</table>
</div>

How it slaps:
- **You:** Clone repo, pick your AI tool, delete the rest.
- **AI:** Reads 31 doc files + structured rules.
- **You:** "Build me a Stripe node with customer CRUD"
- **AI:** Generates production-ready code with proper types, error handling, and routing.

---

## 💥 Why This Slaps Other Methods

Building n8n nodes without context is pain. This repo makes other approaches look ancient.

<table align="center">
<tr>
<td align="center"><b>❌ The Old Way (Pain)</b></td>
<td align="center"><b>✅ The Boilerplate Way (Glory)</b></td>
</tr>
<tr>
<td>
<ol>
  <li>Read 47 pages of n8n docs.</li>
  <li>Copy random code from community nodes.</li>
  <li>Ask AI to help — it hallucinates properties.</li>
  <li>Debug for 3 hours because routing.send is wrong.</li>
  <li>Finally get it working. Realize you forgot credentials.</li>
</ol>
</td>
<td>
<ol>
  <li><code>git clone</code> this repo.</li>
  <li>Pick your AI tool, delete others.</li>
  <li>"Build me a node for X API"</li>
  <li>AI uses 31 doc files + real examples.</li>
  <li>Ship working code. Go grab a coffee. ☕</li>
</ol>
</td>
</tr>
</table>

We're not just giving your AI random docs. We're providing **structured rules, decision trees, code patterns, and working examples** that turn your AI into an n8n expert.

---

## 🚀 Get Started in 90 Seconds

<div align="center">

| Step | Command | What Happens |
|:----:|:--------|:-------------|
| 1️⃣ | `git clone https://github.com/yigitkonur/n8n-community-node-boilerplate.git` | Get the goods |
| 2️⃣ | `cd n8n-community-node-boilerplate && npm install` | Install deps |
| 3️⃣ | Pick your AI tool → delete others (see below) | Clean setup |
| 4️⃣ | `npm run dev` | n8n runs at localhost:5678 |

</div>

### 🧹 Pick Your AI Tool

Choose **one** AI assistant and remove the config files for all others. This prevents conflicts and keeps your AI focused.

<details>
<summary><b>🖱️ Click to expand cleanup commands for each tool</b></summary>

| I use... | Run this to clean up |
|:---------|:---------------------|
| **Cursor** | `rm -rf CLAUDE.md .clinerules .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini .windsurf` |
| **Windsurf** | `rm -rf CLAUDE.md .clinerules .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini .cursor` |
| **Claude Code** | `rm -rf .cursor .windsurf .clinerules .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini` |
| **GitHub Copilot** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .rules .aider.conf.yml .continue .aiassistant .gemini` |
| **Cline** | `rm -rf CLAUDE.md .cursor .windsurf .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini` |
| **Roo-Cline** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini` |
| **Continue.dev** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .rules .aider.conf.yml .github/copilot-instructions.md .aiassistant .gemini` |
| **Aider** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .rules .continue .github/copilot-instructions.md .aiassistant .gemini` |
| **Zed** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant .gemini` |
| **JetBrains AI** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .gemini` |
| **Gemini CLI** | `rm -rf CLAUDE.md .cursor .windsurf .clinerules .roomodes .rules .aider.conf.yml .continue .github/copilot-instructions.md .aiassistant` |

> **💡 Keep `AGENTS.md`** — It's the single source of truth referenced by multiple tools.

</details>

### 🎯 Start Building

```bash
npm run dev  # Opens n8n at http://localhost:5678
```

Now ask your AI:

> "Create a new n8n node for the Stripe API with API key authentication and CRUD operations for customers"

Watch it generate production-ready code. Magic. ✨

---

## ✨ Feature Breakdown: The Secret Sauce

<div align="center">

| Feature | What It Does | Why You Care |
| :---: | :--- | :--- |
| **🤖 11 AI Tools**<br/>`pre-configured` | Rules for Cursor, Windsurf, Claude Code, Copilot, Cline, Roo-Cline, Continue, Aider, Zed, JetBrains, Gemini | Use your favorite tool, rules already set up |
| **📚 31 Doc Files**<br/>`comprehensive` | Every n8n pattern: declarative, programmatic, credentials, routing, pagination, error handling | Your AI has answers before you ask |
| **🏗️ Working Examples**<br/>`copy & modify` | GitHub Issues node with full CRUD, OAuth2, list search, resource operations | Real patterns, not toy examples |
| **🧭 Decision Trees**<br/>`built-in` | REST API? → Declarative. SDK? → Programmatic. Complex auth? → Custom execute | AI knows which pattern to use |
| **📝 AGENTS.md**<br/>`single source of truth` | One master file with all patterns, referenced by all tools | Update once, all tools get smarter |
| **⚡ Hot Reload**<br/>`instant feedback` | `npm run dev` watches your changes | See results immediately |

</div>

---

## 🤖 AI Tool Configuration

<p align="center">
  <a href="#cursor"><img alt="Cursor" src="https://img.shields.io/badge/Cursor-00D9FF?style=for-the-badge&logo=cursor&logoColor=white"></a>
  <a href="#windsurf"><img alt="Windsurf" src="https://img.shields.io/badge/Windsurf-3B82F6?style=for-the-badge"></a>
  <a href="#claude-code"><img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-9333EA?style=for-the-badge&logo=anthropic&logoColor=white"></a>
  <a href="#github-copilot"><img alt="GitHub Copilot" src="https://img.shields.io/badge/GitHub%20Copilot-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>
<p align="center">
  <a href="#cline"><img alt="Cline" src="https://img.shields.io/badge/Cline-FF6B6B?style=for-the-badge"></a>
  <a href="#roo-cline"><img alt="Roo-Cline" src="https://img.shields.io/badge/Roo--Cline-F97316?style=for-the-badge"></a>
  <a href="#continuedev"><img alt="Continue.dev" src="https://img.shields.io/badge/Continue.dev-0EA5E9?style=for-the-badge"></a>
  <a href="#aider"><img alt="Aider" src="https://img.shields.io/badge/Aider-2563EB?style=for-the-badge"></a>
</p>
<p align="center">
  <a href="#zed"><img alt="Zed" src="https://img.shields.io/badge/Zed-084CCF?style=for-the-badge&logo=zed&logoColor=white"></a>
  <a href="#jetbrains-ai"><img alt="JetBrains AI" src="https://img.shields.io/badge/JetBrains%20AI-000000?style=for-the-badge&logo=jetbrains&logoColor=white"></a>
  <a href="#gemini-cli"><img alt="Gemini CLI" src="https://img.shields.io/badge/Gemini%20CLI-4285F4?style=for-the-badge&logo=google&logoColor=white"></a>
</p>

Each AI assistant has custom-configured rules optimized for n8n node development. Click to expand details.

<details>
<summary><b>🖥️ Cursor</b></summary>

**Config Files:**
```
.cursor/rules/
├── n8n-node-development.mdc   # Main rules (344 lines)
├── credentials.mdc            # Credential-specific rules
└── documentation.mdc          # Doc navigation helper
```

**Why these files:** Cursor uses MDC format (Markdown + YAML frontmatter) with glob patterns to auto-attach rules when editing specific file types.

**Key Features:**
- `globs: ["nodes/**/*.ts", "credentials/**/*.ts"]` — Auto-applies to n8n source files
- `alwaysApply: false` — Only loads when relevant files are open
- Excludes `node_modules/**` and `dist/**`

</details>

<details>
<summary><b>🏄 Windsurf</b></summary>

**Config Files:**
```
.windsurf/rules/
├── n8n-node-development.md    # Main rules (180 lines)
├── credentials.md             # Credential-specific rules
└── documentation.md           # Doc navigation helper
```

**Why these files:** Windsurf supports glob-triggered rules that auto-apply based on file patterns.

**Key Features:**
- `trigger: glob` with `globs: ["nodes/**/*.ts"]` — Auto-applies to n8n source files
- Separate credential rules for `credentials/**/*.ts`
- Doc navigation for `docs/**/*.md`

</details>

<details>
<summary><b>🟣 Claude Code</b></summary>

**Config Files:**
```
CLAUDE.md                      # Project rules (165 lines)
AGENTS.md                      # Detailed reference (445 lines)
```

**Why these files:** Claude Code reads `CLAUDE.md` from the project root as its primary instruction file.

**Key Features:**
- Key commands section for quick reference
- Decision tree in prose format
- Pattern examples with inline comments
- References to all 31 documentation files

</details>

<details>
<summary><b>⬛ GitHub Copilot</b></summary>

**Config Files:**
```
.github/
└── copilot-instructions.md    # Repository instructions (227 lines)
```

**Why this file:** GitHub Copilot reads `.github/copilot-instructions.md` for repository-level context.

**Key Features:**
- Technology stack table
- ASCII decision tree for quick parsing
- Routing types reference table
- Complete 31-file documentation index

</details>

<details>
<summary><b>🔴 Cline</b></summary>

**Config Files:**
```
.clinerules                    # Project rules (126 lines)
```

**Why this file:** Cline (VS Code extension) reads `.clinerules` for project-specific instructions.

**Key Features:**
- Architecture decision matrix
- File structure with annotations
- SDK execution pattern template
- Common mistakes as bullet points

</details>

<details>
<summary><b>🟠 Roo-Cline</b></summary>

**Config Files:**
```
.roomodes                      # Custom modes (264 lines, YAML)
```

**Why this file:** Roo-Cline supports custom "modes" that define different AI personas with specific file access permissions.

**Key Features:**
- **n8n-node-developer** — Full access to nodes/ and credentials/
- **n8n-credential-developer** — Focused on credentials/ only
- **n8n-docs-navigator** — Read-only mode for documentation help

</details>

<details>
<summary><b>🔵 Continue.dev</b></summary>

**Config Files:**
```
.continue/rules/
└── n8n-rules.md               # Project rules (144 lines)
```

**Why this file:** Continue.dev uses a `rules/` directory for project-specific markdown instructions.

**Key Features:**
- Uses `@nodes/GithubIssues/` syntax for file references
- Table-based common mistakes guide
- Integration with Continue's context system

</details>

<details>
<summary><b>🔷 Aider</b></summary>

**Config Files:**
```
.aider.conf.yml                # Aider configuration (33 lines)
AGENTS.md                      # Read by Aider automatically
```

**Why these files:** Aider uses `.aider.conf.yml` for project configuration and automatically reads files listed in the `read:` section.

**Key Features:**
- `read:` section loads AGENTS.md and key docs
- `lint-cmd: npm run lint` — Auto-lint after changes
- `auto-lint: true` — Automatically run linter

</details>

<details>
<summary><b>⚡ Zed</b></summary>

**Config Files:**
```
.rules                         # Zed rules (58 lines)
```

**Why this file:** Zed reads `.rules` from the project root for AI assistant context.

**Key Features:**
- Ultra-compact format (58 lines)
- Essential commands and patterns only
- Reference file paths for deeper context

</details>

<details>
<summary><b>⬛ JetBrains AI</b></summary>

**Config Files:**
```
.aiassistant/rules/
└── n8n-rules.md               # AI Assistant rules (151 lines)
```

**Why this file:** JetBrains AI Assistant reads from `.aiassistant/rules/` directory for project-specific instructions.

**Key Features:**
- Table-formatted technology stack
- Decision tree with clear branching
- IDE-friendly markdown structure

</details>

<details>
<summary><b>🔵 Gemini CLI</b></summary>

**Config Files:**
```
.gemini/
└── settings.json              # Gemini configuration (JSON)
```

**Why this file:** Gemini CLI uses JSON configuration for project context.

**Key Features:**
- `projectContext` with description and rules reference
- `codeStyle` preferences for TypeScript strict mode
- `keyReferences` pointing to example files

</details>

---

## 📚 Documentation (31 Files)

Your AI has access to comprehensive n8n documentation. Every pattern, every gotcha, every best practice.

<details>
<summary><b>📖 Click to see all 31 documentation files</b></summary>

| # | File | Purpose |
|:-:|:-----|:--------|
| 00 | `documentation-index.md` | Master index |
| 01 | `project-structure-overview.md` | Repository layout |
| 02 | `package-json-configuration.md` | npm setup |
| 03 | `typescript-configuration.md` | tsconfig.json |
| 04 | `node-anatomy-and-architecture.md` | Node structure |
| 05 | `declarative-vs-programmatic-nodes.md` | Architecture choice |
| 06 | `node-properties-reference.md` | Property types |
| 07 | `credentials-system-overview.md` | Auth overview |
| 08 | `api-key-credentials.md` | API key auth |
| 09 | `oauth2-credentials.md` | OAuth2 auth |
| 10 | `creating-your-first-node.md` | Tutorial |
| 11 | `resources-and-operations.md` | Multi-resource |
| 12 | `declarative-routing.md` | routing.send |
| 13 | `custom-execute-methods.md` | execute() |
| 14 | `list-search-methods.md` | Dropdowns |
| 15 | `resource-locators.md` | Multi-mode inputs |
| 16 | `pagination-handling.md` | Pagination |
| 17 | `error-handling-patterns.md` | Errors |
| 18 | `helper-functions-and-utilities.md` | Utilities |
| 19 | `external-sdk-integration.md` | SDK patterns |
| 20 | `icons-and-branding.md` | SVG icons |
| 21 | `node-json-metadata.md` | node.json |
| 22 | `development-workflow.md` | Dev workflow |
| 23 | `testing-strategies.md` | Testing |
| 24 | `linting-and-code-quality.md` | ESLint |
| 25 | `preparing-for-publication.md` | Pre-publish |
| 26 | `publishing-to-npm.md` | npm publish |
| 27 | `n8n-cloud-verification.md` | Cloud verification |
| 28 | `complete-code-examples.md` | Examples |
| 29 | `common-patterns-and-recipes.md` | Recipes |
| 30 | `troubleshooting-guide.md` | Troubleshooting |

</details>

---

## 🏗️ Project Structure

```
n8n-community-node-boilerplate/
├── 🤖 AI Tool Configs
│   ├── .cursor/rules/              # Cursor (MDC format)
│   ├── .windsurf/rules/            # Windsurf (glob triggers)
│   ├── .continue/rules/            # Continue.dev
│   ├── .github/copilot-instructions.md  # GitHub Copilot
│   ├── .aiassistant/rules/         # JetBrains AI
│   ├── .gemini/settings.json       # Gemini CLI
│   ├── CLAUDE.md                   # Claude Code
│   ├── .clinerules                 # Cline
│   ├── .roomodes                   # Roo-Cline
│   ├── .rules                      # Zed
│   └── .aider.conf.yml             # Aider
│
├── 📝 AGENTS.md                    # Single source of truth (all tools reference this)
│
├── 🔐 credentials/                 # Auth implementations
│   ├── GithubIssuesApi.credentials.ts      # API key example
│   └── GithubIssuesOAuth2Api.credentials.ts # OAuth2 example
│
├── 🔌 nodes/                       # Node implementations
│   ├── Example/                    # Programmatic pattern
│   └── GithubIssues/               # Declarative pattern (full CRUD)
│       ├── resources/              # Per-resource operations
│       ├── listSearch/             # Dynamic dropdowns
│       └── shared/                 # Reusable utilities
│
└── 📚 docs/                        # 31 documentation files
```

---

## ⚡ Commands

<div align="center">

| Command | What It Does |
|:--------|:-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start n8n with hot reload at localhost:5678 |
| `npm run build` | Compile TypeScript |
| `npm run lint` | Check code quality |
| `npm run lint:fix` | Auto-fix lint issues |
| `npm run release` | Create new release |

</div>

---

## 🔥 Common Issues & Quick Fixes

<details>
<summary><b>Expand for troubleshooting tips</b></summary>

| Problem | Solution |
|:--------|:---------|
| **AI generates wrong routing.send type** | Make sure your AI tool config is loading. Check `AGENTS.md` is present. |
| **Node doesn't appear in n8n** | Run `npm run build` then restart `npm run dev`. Check `package.json` registration. |
| **TypeScript errors on build** | Check imports are at top of file. Verify `INodeType` implementation. |
| **Credentials not working** | Verify credential name in node matches credential file export. |
| **Hot reload not working** | Kill all n8n processes and restart `npm run dev`. |

</details>

---

## 📦 What's Included

<div align="center">

| Component | Files | Description |
|:----------|:-----:|:------------|
| **AI Configs** | 11 | Pre-configured rules for every major AI coding assistant |
| **Documentation** | 31 | Comprehensive guides from basics to advanced patterns |
| **Example Nodes** | 2 | Working GitHub Issues (declarative) + Example (programmatic) |
| **Credentials** | 2 | API Key + OAuth2 authentication examples |
| **TypeScript** | ✅ | Strict mode, proper types, ESLint configured |

</div>

---

## 🌟 Resources

<div align="center">

| Resource | Link |
|:---------|:-----|
| **n8n Creating Nodes** | [docs.n8n.io/integrations/creating-nodes](https://docs.n8n.io/integrations/creating-nodes/) |
| **n8n Community Forum** | [community.n8n.io](https://community.n8n.io/) |
| **n8n Creator Portal** | [creators.n8n.io/nodes](https://creators.n8n.io/nodes) |

</div>

---

<div align="center">

## 📄 License

MIT License — see [LICENSE.md](LICENSE.md)

---

**Built with 🔥 because manually explaining n8n to AI is a soul-crushing waste of time.**

</div>

