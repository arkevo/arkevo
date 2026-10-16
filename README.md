## Hi, I'm Ivo 👋

🛒 Amazon by day, side quests by night | 🤖 Agentic engineering with Claude Code | 🎬 Building [Frametage](https://frametage.com)

`Python` `Dart` `Flutter` `FFmpeg` `NVENC` `PyTorch` `Claude Code` `Cloudflare Workers` `Postgres`

### Start Here

🧵 **[beadspowers-python](https://github.com/arkevo/beadspowers-python)** - a structured plan → execute → verify workflow for building Python with Claude Code<br>
🎞️ **[Frametage-Encoder-Autoframer](https://github.com/arkevo/Frametage-Encoder-Autoframer)** - turn landscape video into a vertical clip that follows the people, then encode it for phones

### Current Projects

#### 🧵 [beadspowers-python](https://github.com/arkevo/beadspowers-python)

A Claude Code workflow for Python projects that joins two tools and enforces the order between them: [Beads](https://github.com/steveyegge/beads), a git-backed issue tracker that gives agents a durable memory of what is planned, running and done, and Superpowers, a plan → execute → verify lifecycle. For a single task you stay in the loop: Claude picks how much planning the work deserves, asks the questions that matter, builds test-first and verifies at a depth sized to the diff. For an epic, a brainstormed spec becomes sequenced waves of tasks, open questions are answered with throwaway spikes before anything depends on them, and the approved plans run as parallel agents, each in its own git worktree. Every task is checked with ruff, mypy and pytest, plus review agents and an adversarial pass at the full tier, and progress lives in Beads labels, so an interrupted run resumes exactly where it stopped.

#### 🎞️ [Frametage-Encoder-Autoframer](https://github.com/arkevo/Frametage-Encoder-Autoframer) (`ftea`)

Most film is shot in landscape and most phones are held upright, and a centre crop cuts out whoever isn't standing in the middle. `ftea` finds the people and faces in each shot, chooses a subject, and moves a smoothed virtual camera to follow them the way an operator would, keeping title cards readable. It then encodes the vertical video scene by scene with NVIDIA NVENC to a VMAF quality target, so quiet scenes spend fewer bits than busy ones, and packages six HLS variants (AV1 and H.264 at 1080p, 720p and 360p) with a bundled player you can watch on your phone over your own Wi-Fi. It is the encoding pipeline behind [Frametage](https://frametage.com), released as Apache-2.0 so creators get a free tool and anyone can see how it works.

### GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/arkevo)

### What I'm Doing

- **Agentic engineering** - building the workflows that let coding agents plan, test and ship real software, with a human in the loop where it counts
- **Frametage** - a phone app for watching film clips in vertical, powered by the pipeline above
- **Open-sourcing what I build** - so the tools are useful on their own, not just inside my projects
