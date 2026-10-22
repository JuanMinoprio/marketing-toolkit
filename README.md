# Marketing Toolkit

**Free, open-source AI tools for marketers — built by a marketer, not a SaaS company.**

Every tool here is a Claude Code plugin: it runs locally in your terminal, reads nothing it shouldn't, and installs in one command. No signup, no email gate, no rate limits.

Built for marketers in regulated environments — where "just paste it into some AI tool" isn't an option and every workflow has to survive compliance review.

## The tools

| Tool | Use it when… | Install |
|------|--------------|---------|
| [aeo-scorer](https://github.com/JuanMinoprio/aeo-scorer) | You want AI engines (Google AIO, ChatGPT, Perplexity) to cite your content. Scores drafts on a 6-dimension, 100-point rubric calibrated against 37 cited 2026 studies. | `/plugin install aeo-scorer --marketplace JuanMinoprio/aeo-scorer` |
| [hook-lab](https://github.com/JuanMinoprio/hook-lab) | You have a LinkedIn hook and want to know if it stops the scroll — before you post. 20 variations, 5-persona AI jury, ranked leaderboard. | `/plugin install hook-lab --marketplace JuanMinoprio/hook-lab` |
| [advisory-board](https://github.com/JuanMinoprio/advisory-board) | You're about to commit to a decision and want it stress-tested from six angles first. | `/plugin install advisory-board --marketplace JuanMinoprio/advisory-board` |

**Want all three?** Add the catalog once, then install any tool from it:

```
/plugin marketplace add JuanMinoprio/claude-plugins
/plugin install aeo-scorer@JuanMinoprio
```

On Claude Code older than 2.1.275, the one-line installs above need two steps: `/plugin marketplace add JuanMinoprio/<tool>`, then `/plugin install <tool>@<tool>`.

**No AI needed:** aeo-scorer also ships an offline CLI that scores drafts in milliseconds and can gate content in CI. See [its README](https://github.com/JuanMinoprio/aeo-scorer#offline-cli-no-claude-no-api-key).

## What is Claude Code?

Claude Code is Anthropic's free CLI that runs Claude directly in your terminal. Install it once ([2-minute setup](https://docs.anthropic.com/claude/claude-code)) and every tool above works from any project.

## Roadmap

This toolkit grows one tool at a time — each new tool ships alongside the post that explains the system behind it. The full toolkit (setup videos, templates, prompt libraries) launches **October 2026**, permanently free.

## Privacy and secrets

None of these tools needs an API key, token, or account. They run inside your own Claude Code session, and personal config stays on your machine.

## Want this built for your team?

I build AI tools and workflows for marketing teams: systems like these, scoped to your stack, your data, and your compliance rules.

**[Start a conversation](https://juanminoprio.com/?utm_source=github&utm_medium=readme&utm_campaign=marketing-toolkit#contact)** or email hello@juanminoprio.com.

## Who's behind this

[Juan Minoprio](https://juanminoprio.com) — systems-thinking marketer in regulated finance. I publish twice a week on [LinkedIn](https://www.linkedin.com/in/juanminoprio/) about consumer psychology and AI for marketing.
