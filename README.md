# Snehal Reddy Yelmati

I work on what it takes to run LLM agents well: how to split work across them, what
they cost, and how to tell whether they did the job. That has meant building a parallel
coding-agent harness, a browser-use runtime, and knowledge-graph pipelines that give
models better context than raw text. Currently founding AI engineer at a stealth
startup, building local-first AI with on-device knowledge-graph extraction and
retrieval. Before that, five years at DBS Bank across backend engineering and applied ML.

## Selected work

| Project | What it is | Result |
|---|---|---|
| [Fanout](https://github.com/snehalyelmati/fanout) | Parallel coding-agent harness. A coordinator turns a repo task into a dependency-aware plan; workers run in isolated Git worktrees, integration is verified, and every run is traced. | -42% cost vs. a single-agent baseline on open-weight models, independently checked |
| [Zip](https://github.com/snehalyelmati/zip) | Browser-use agent runtime: CDP snapshots, stable element IDs, DOM-first tools, Oracle/Filter/Worker modes. | 86.4% on the MiniWoB++ full suite (125 episodes, 0 errors); benchmark cost $38.80 to $7.15 |
| [pi-doubleword-provider](https://pi.dev/packages/@snehalyelmati/pi-doubleword-provider) | Doubleword.ai model provider for the Pi coding agent, with realtime and async tiers. | Published on the Pi registry; documented in [Doubleword's Pi integration guide](https://docs.doubleword.ai/inference-api/integrations/pi) |
| [pi-tmux-sidechat](https://github.com/snehalyelmati/pi-tmux-sidechat) | Read-only side-chat over a running Pi session in tmux (`/scc`). | Published on the Pi registry |

Earlier agent work: [Morpher](https://github.com/Onyx-AI-Studio/morpher) (2023), a
from-scratch plan-and-execute agent that replans after every action, and
[Rex](https://github.com/snehalyelmati/rex) (2025), the same idea on LangGraph and MCP
with LangSmith tracing.
