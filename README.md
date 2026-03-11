# AI Governor Framework
### The Keystone for AI-Driven Code

**Stop fighting your AI assistant. Start governing it.**

Tired of AI-generated code that's buggy, inconsistent, and ignores your architecture? The AI Governor Framework is a safe, plug-and-play system designed to teach your AI your project's unique DNA. It provides a set of rules and workflows to turn any AI assistant from a chaotic tool into a disciplined engineering partner that respects your architectural decisions, best practices, and non-negotiable constraints.

Reclaim control. Enforce your coding standards. Ship with confidence.

---                                                                                                                                                        
**⚠️  This project has been superseded by [GAAI — Governed Agentic AI Infrastructure](https://github.com/Fr-e-d/GAAI-framework).**
  
GAAI is the production-ready evolution of this framework — dual-track agents, persistent memory, skill-based execution, and a full decision trail. Battle-tested on 176 stories, 177 decisions, 84,000 lines of TypeScript.

**→ [Go to GAAI](https://github.com/Fr-e-d/GAAI-framework)**

---

## ✨ The Philosophy: From Prompting & Fixing to Governing
This approach is rooted in one core principle: **Context Engineering**.

This isn't about bigger prompts or dumping your entire codebase into one, which is both ineffective and expensive. It's about giving the AI the *right information* at the *right time*. This framework achieves that by building a knowledge base of robust `rules` (the orders) and architectural `READMEs` (the context) that the AI consults on-demand.

> #### Architectural Choice: An In-Repo Knowledge Base
>
> This framework is built on a simple, robust principle: **Treat your project's knowledge base like your codebase.**
>
> We leverage an **In-Repo** approach, keeping all governance rules and architectural context directly inside the repository. This makes the AI's knowledge base:
> -   **Simple & Efficient:** Zero network latency and no complex external systems.
> -   **Evolutive & Maintainable:** The AI's context evolves in lock-step with your code.
> -   **Auditable & Versioned:** Every change is tracked in `git`, providing a clear, human-readable history.
> -   **Portable & Robust:** Any developer can clone the repo and have the full, up-to-date context instantly, ensuring stability and consistency.
>
> For complex external documentation, such as third-party APIs or external library, this in-repo system can be seamlessly combined with a RAG-based MCP server, such as Context7, to fetch and inject that external knowledge on demand. This leverages the best of both worlds: robust and versioned in-Repo governance for your internal architecture, and dynamic, on-demand context for external dependencies.

This is how we shift from the endless loop of **prompting and fixing** to strategic **Governing**.

---

## 🚀 How It Works: Two Core Components

The AI Governor Framework is composed of two distinct but complementary parts:

| Component | What It Is | How It's Used |
| :--- | :--- | :--- |
| **The Governance Engine** (`/rules`) | A set of powerful, passive rules that run in the background. | Your AI assistant discovers and applies these rules **automatically** to ensure quality and consistency. |
| **The Operator's Playbook** (`/dev-workflow`) | A set of active, step-by-step protocols for the entire development lifecycle. | You **manually** invoke these protocols to guide the AI through complex tasks like planning and implementation. |

### A Battle-Tested Workflow for Quality at Scale
The dev-workflow is now reinforced with a comprehensive suite of review protocols for code quality, security, and architecture. This new system is inspired by the successful, battle-tested workflows used by Anthropic's own team to build products like Claude Code.

Key changes include:
- A new, 7-layer quality audit protocol for robust validation.
- Simplified and clarified all workflow steps for better readability.
- Rewrote all documentation to focus on universal software engineering principles.

By adopting these proven strategies for structured AI collaboration, the framework provides a more robust and predictable path from idea to production-ready code.

#### At a Glance: The Operator's Playbook
> The framework is built around a series of sequential protocols that move a feature from idea to production with clarity and control:
> -   0️⃣ **Bootstrap:** Turns a generic AI into a project-specific expert. (One-Time Setup)
> -   1️⃣ **Define:** Transforms an idea into a detailed PRD.
> -   2️⃣ **Plan:** Converts the PRD into a step-by-step technical plan.
> -   3️⃣ **Implement & Review:** Executes the plan, followed by a mandatory quality audit (`4-quality-audit.md`) and a process retrospective (`5-implementation-retrospective.md`) to continuously improve the system.

---

## ▶️ Get Started

Ready to install the framework and run your first governed task?


## 3. Quick Start: Installation

This guide provides a safe, non-destructive process to integrate the framework into any project.

**1. Clone the Framework**

Open a terminal at the root of your project and run the following command:
```bash
git clone https://github.com/Fr-e-d/AI-Governor-Framework.git .ai-governor
```
This downloads the entire framework into a hidden `.ai-governor` directory within your project.

**2. Configure for Your Assistant**

The final step depends on your AI assistant. Choose the relevant section below.

#### For Cursor Users
To get the best experience, including custom commands like `/review`, copy both the rules and the prompts into your project's `.cursor` directory.
```bash
# Copy governance rules
mkdir -p .cursor/rules && cp -r .ai-governor/rules/* .cursor/rules/

# Copy custom prompts for an enhanced workflow
mkdir -p .cursor/prompts && cp -r .ai-governor/.cursor/prompts/* .cursor/prompts/
```

#### For Claude Code Users
To enable custom commands like `/review`, copy the command definitions into your project's `.claude` directory.
```bash
mkdir -p .claude/commands && cp -r .ai-governor/.claude/commands/* .claude/commands/
```

#### For Other AI Assistants (e.g., OpenCode)
The framework is ready to use without extra steps. Your assistant will find its boot sequence (`CLAUDE.md` or `OpenCode.md`) and the necessary rules within the `.ai-governor` directory.


> [!NOTE]
> ## Ready to Start?
>
> **[➡️ Go to the Full Workflow Guide](./dev-workflow)**
>
> Got questions or ideas?
>
> **[🗣️ Join the Community on GitHub Discussions](https://github.com/Fr-e-d/The-Governor-Framework/discussions)**


## ❤️ Support This Project

If you find this framework valuable, please consider showing your support. It is greatly appreciated!

-   **[Sponsor on GitHub](https://github.com/sponsors/Fr-e-d)**

## 🤝 Attribution & License

This framework is an enhanced and structured adaptation inspired by the foundational work on AI-driven development by [snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks).

It is shared under the **Apache 2.0 License**. See the `LICENSE` file for more details. For contribution guidelines, please see `CONTRIBUTING.md`. 
