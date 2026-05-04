<div align="center">
<img src="assets/claude-hacks-logo.png" width="400" alt="Claude Hacks Logo" />
</div>

# Claude Hacks
[![Claude](https://img.shields.io/badge/Claude-Hacks-orange)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-red)]()

A handpicked collection of Claude hacks, prompts, and resources to unlock more power, speed, and creativity from your AI workflows.

## Useful
- [Claude Obsidian](https://github.com/AgriciDaniel/claude-obsidian): Claude + Obsidian knowledge companion. A running notetaker that builds and maintains a persistent, compounding wiki vault. Every source you add gets integrated. Every question you ask pulls from everything that has been read.
- [How Boris Cherny Uses Claude Code](https://howborisusesclaudecode.com/)
- [Claude Code Templates](https://github.com/davila7/claude-code-templates): CLI tool for configuring and monitoring Claude Code
- [Everything Claude Code](https://github.com/affaan-m/everything-claude-code): About
The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond
- [AI Website Cloner Template](https://github.com/JCodesMore/ai-website-cloner-template): A reusable template for reverse-engineering any website into a clean, modern Next.js codebase using AI coding agents
- [Paperclip](https://github.com/paperclipai/paperclip): Open-source orchestration for zero-human companies

## Skills
- [Promp Master](https://github.com/nidhinjs/prompt-master): A Claude skill that writes the accurate prompts for any AI tool. Zero tokens or credits wasted. Full context and memory retention


## CLAUDE.md
After every correction, end with: **"Update your CLAUDE.md so you don't make that mistake again."** Claude is eerily good at writing rules for itself.
> Ruthlessly edit your CLAUDE.md over time. Keep iterating until Claude's mistake rate measurably drops.

## Use Subagents
- Append "use subagents" to any request where you want Claude to throw more compute at the problem.
- Offload individual tasks to subagents to keep your main agent's context window clean and focused.
- Route permission requests to Opus 4.5 via a hook — let it scan for attacks and auto-approve the safe ones.

## Level Up Your Prompting
- **Challenge Claude.** Say "Grill me on these changes and don't make a PR until I pass your test." Make Claude be your reviewer. Or, say "Prove to me this works" and have Claude diff behavior between main and your feature branch.
- **After a mediocre fix**, say: "Knowing everything you know now, scrap this and implement the elegant solution."
- **Write detailed specs** and reduce ambiguity before handing work off. The more specific you are, the better the output.

> Don't accept the first solution. Push Claude to do better — it usually can.


## Commands

### Auto Mode — A Safer Way to Skip Permissions
```claude --enable-auto-mode```
> Instead of approving every file write and bash command, or skipping permissions entirely with --dangerously-skip-permissions, auto mode lets Claude make permission decisions on your behalf.

### /simplify — Improve Code Quality
Use parallel agents to **improve code quality**, tune code efficiency, and ensure CLAUDE.md compliance. Just append /simplify to any prompt.
```hey claude make this code change then run /simplify```
> Runs parallel agents that review your changed code for reuse opportunities, quality issues, and efficiency improvements — all in one pass.



### /schedule — Cloud Jobs
```/schedule a daily job ...```
> Use /schedule to create recurring cloud-based jobs for Claude, directly from the terminal. Unlike /loop (which runs locally for up to 3 days), scheduled jobs run in the cloud — they work even when your laptop is closed.
