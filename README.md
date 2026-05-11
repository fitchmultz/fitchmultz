# Mitch Fultz

I build local-first AI developer tools and agent workflow infrastructure: focused Pi extensions, CueLoop for queue-driven coding-agent work, and operational systems for governance, scraping, and verification.

## Start here

These are the six projects I keep pinned. They show the current center of gravity: agent workflow tools, browser/model extensions for Pi, one larger coding-agent workflow system, and one governance/control-plane reference implementation.

| Project | What it does | Start here |
|---|---|---|
| [`CueLoop`](https://github.com/fitchmultz/cueloop) | Local-first queue for auditable coding-agent work | [Workflow diagram](https://github.com/fitchmultz/cueloop#what-you-are-seeing) |
| [`pi-codex-goal`](https://github.com/fitchmultz/pi-codex-goal) | Goal tracking and continuation for long Pi sessions | [Install and commands](https://github.com/fitchmultz/pi-codex-goal#install) |
| [`pi-oracle`](https://github.com/fitchmultz/pi-oracle) | ChatGPT web handoff extension for Pi | [Successful-run transcript](https://github.com/fitchmultz/pi-oracle#what-a-successful-run-looks-like) |
| [`pi-agent-browser-native`](https://github.com/fitchmultz/pi-agent-browser-native) | Native browser automation tool for Pi agents | [Browser workflow examples](https://github.com/fitchmultz/pi-agent-browser-native#what-this-looks-like-in-pi) |
| [`pi-cursor-sdk`](https://github.com/fitchmultz/pi-cursor-sdk) | Cursor SDK provider extension for Pi models | [Quick start](https://github.com/fitchmultz/pi-cursor-sdk#quick-start) |
| [`AI Control Plane`](https://github.com/fitchmultz/ai-control-plane) | Host-first AI governance reference implementation | [Architecture and boundary](https://github.com/fitchmultz/ai-control-plane#support-boundary) |

## If you are reviewing my work

- For focused agent-tooling packages, start with the Pi extension repos above.
- For a larger workflow system, open [`CueLoop`](https://github.com/fitchmultz/cueloop).
- For systems and operator thinking, open [`AI Control Plane`](https://github.com/fitchmultz/ai-control-plane), [`Spartan Scraper`](https://github.com/fitchmultz/spartan-scraper), or [`Splunk TUI`](https://github.com/fitchmultz/splunk-tui).
- For end-to-end demo surfaces, open [`Promo Studio`](https://github.com/fitchmultz/promo-studio), [`agent-eval`](https://github.com/fitchmultz/agent-eval), or [`Ricochet Rush`](https://github.com/fitchmultz/ricochet-rush).

## Pi extension suite

Each public Pi extension is intentionally small and focused:

- [`pi-codex-goal`](https://github.com/fitchmultz/pi-codex-goal) — goal tracking and continuation for long Pi sessions.
- [`pi-agent-browser-native`](https://github.com/fitchmultz/pi-agent-browser-native) — native `agent_browser` tool for controlled browser automation in Pi.
- [`pi-oracle`](https://github.com/fitchmultz/pi-oracle) — ChatGPT web handoff for hard or long-running tasks with archives, async jobs, and saved results.
- [`pi-cursor-sdk`](https://github.com/fitchmultz/pi-cursor-sdk) — Cursor SDK provider that adds Cursor models to Pi's native model picker.
- [`pi-edit-session-in-place`](https://github.com/fitchmultz/pi-edit-session-in-place) — re-edit or delete an earlier user message in the current session branch.
- [`pi-zai-mcp`](https://github.com/fitchmultz/pi-zai-mcp) — Z.ai MCP server bridge for web search, URL/repository reading, and vision workflows in Pi.
- [`pi-stash`](https://github.com/fitchmultz/pi-stash) — stash draft messages and restore them later.
- [`pi-local-agents-only`](https://github.com/fitchmultz/pi-local-agents-only) — strip global `AGENTS.md` and `CLAUDE.md` instructions for selected projects.
- [`pi-copy-user-message`](https://github.com/fitchmultz/pi-copy-user-message) — copy the most recent user message to the clipboard.

## More work worth opening

| Project | What it shows | Start here |
|---|---|---|
| [`Spartan Scraper`](https://github.com/fitchmultz/spartan-scraper) | Local-first scraping and research workbench in Go | [5-minute demo](https://github.com/fitchmultz/spartan-scraper#5-minute-demo) |
| [`Promo Studio`](https://github.com/fitchmultz/promo-studio) | Codex commerce demo with receipts, diffs, transcripts, and validation | [What you are seeing](https://github.com/fitchmultz/promo-studio#what-you-are-seeing) |
| [`agent-eval`](https://github.com/fitchmultz/agent-eval) | Transcript-first evaluation across Codex, Claude Code, and Pi sessions | [Outputs](https://github.com/fitchmultz/agent-eval#outputs) |
| [`Ricochet Rush`](https://github.com/fitchmultz/ricochet-rush) | 3D browser game with generated board design and local fallback play | [Demo and QA](https://github.com/fitchmultz/ricochet-rush#demo-and-qa) |
| [`Morphio`](https://github.com/fitchmultz/morphio) | AI-assisted content workflow monorepo with FastAPI, Next.js, and native routines | [Visual tour](https://github.com/fitchmultz/morphio#visual-tour) |
| [`Splunk TUI`](https://github.com/fitchmultz/splunk-tui) | Rust CLI/TUI for Splunk diagnostics and local-first verification | [Quick validation](https://github.com/fitchmultz/splunk-tui#quick-validation) |
| [`Cloop`](https://github.com/fitchmultz/cloop) | Local loop/task and knowledge assistant, separate from CueLoop | [Architecture at a glance](https://github.com/fitchmultz/cloop#architecture-at-a-glance) |

## What I focus on

- Agent workflow infrastructure
- Local-first AI developer tools
- Browser/native automation for coding agents
- Auditable execution, receipts, and verification
- Operational CLIs and control-plane patterns

## How I try to make projects reviewable

- Show the outcome before setup when a README is meant for public review.
- Include verification commands, local smoke paths, or proof artifacts where practical.
- Make status and limits explicit instead of implying maturity that is not there.
- Prefer local-first tools that leave inspectable files, logs, receipts, or reports behind.

## Links

- Portfolio / writing: [FitchHub.com](https://FitchHub.com)
- GitHub: [github.com/fitchmultz](https://github.com/fitchmultz)
- LinkedIn: [linkedin.com/in/mitchelfultz](https://www.linkedin.com/in/mitchelfultz)
- X: [x.com/fitchmultz](https://x.com/fitchmultz)
