<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="/assets/banner-dark.svg">
  <img src="/assets/banner-light.svg" 
        alt="runkora: The open source control plane for running agent factories in production."
        width="100%">
</picture>

<p align="center">
  <b>runkora</b> takes your agents from proof of concept into production.
</p>

<p align="center">
  <a href="https://github.com/runkora/kora">kora</a> ·
  <a href="https://github.com/runkora/kora/blob/main/docs/guides/deployment.md">deployment</a> ·
  <a href="https://github.com/runkora/kora/blob/main/ARCHITECTURE.md">architecture</a> ·
  <a href="https://runkora.dev">docs</a> ·
  <a href="https://runkora.io">website</a>
</p>

Every agent use case you might want to ship comes down to:

* **How does an agent run?**
* **Who is the agent?**
* **What stops it from doing damage?**
* **What can it talk to?**

An agent on a laptop runs with its developer's credentials and leaves no audit trail of what it did. runkora makes those agents safe to run at scale. It is not an agent framework, a model router, or an LLM wrapper. It runs the agent harnesses you already use, such as Claude Code, Codex and OpenCode, on Kubernetes, and governs everything they do.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/assets/console-dark.png">
  <img src="/assets/console-light.png" alt="The kora console Agents page: agent count, active and completed runs, token use, spend by agent, and the runs in progress." width="100%">
</picture>

## What teams build on runkora

* Review and context agents that take part in every pull request.
* Fleet-wide changes shipped as the same pull request to every team.
* Incident agents that triage an alert and start root cause analysis before anyone is paged.
* Bug-hunting agents that run weekly and explore your applications and codebases.
* General purpose coding agents that pick up work from your task or issue boards.
