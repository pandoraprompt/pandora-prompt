# PandoraPrompt

Once opened, you can't close the box again.

PandoraPrompt is a project exploring what happens when you run AI without guardrails, without cloud dependencies, and without anyone else controlling what the model is allowed to say. It sits at the intersection of uncensored open-source LLMs, local AI agents, and privacy-first infrastructure.

## What this is about

The AI tools most people use today — ChatGPT, Claude, Gemini — are powerful but come with constraints. They run on someone else's hardware, cost money per query, and are filtered through layers of content policies that decide what you're allowed to ask and what the model is allowed to answer.

PandoraPrompt starts from a different premise: what if you owned the entire stack? Your hardware, your models, your rules. No data leaving your machine. No per-token costs. No one deciding that your question is too sensitive.

This matters especially for professionals who handle confidential information — lawyers, financial advisors, healthcare providers — and for anyone who believes that general-purpose AI should be a tool you control, not a service you rent.

## Current focus

**Local AI agents with enterprise-grade isolation.** Running NVIDIA's NemoClaw stack on dedicated hardware (DGX Spark), with kernel-level sandboxing, policy-based network control, and local inference via Ollama. Models up to 120 billion parameters running entirely offline.

**Uncensored model evaluation.** Systematic comparison of open models with and without content filters, exploring where guardrails help and where they get in the way of legitimate use cases.

**Privacy-first architecture.** Designing AI workflows where sensitive data never leaves the client's infrastructure. From inference to agent orchestration, everything runs locally.

## Where this is going

**Consulting and deployment** — helping organizations in regulated industries (legal, finance, healthcare) adopt local AI that meets their compliance requirements. The technology works today; PandoraPrompt is building the expertise and tooling to make it accessible.

**Product development** — building towards AI services that prioritize user sovereignty over platform lock-in. Details to follow.

## Note on this repository

Development happens on GitLab. This GitHub repository serves as a public mirror for visibility and discoverability. For the latest code, issues, and CI/CD, head to the GitLab project.

## Tech philosophy

This project follows the [Choose Boring Technology](https://boringtechnology.club) school of thought. Proven tools over trendy ones. Ship stuff, then iterate. Innovation tokens are spent on the product, not the infrastructure.

## Contact

For collaboration, consulting inquiries, or partnership opportunities:

pandoraprompt@pm.me · [pandoraprompt.com](https://pandoraprompt.com)

---

*Founded March 2026.*
