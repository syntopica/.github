<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-inverse.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg">
  <img src="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg" alt="Syntopica" width="420">
</picture>

Syntopica is a personal wiki that an agent maintains and a person owns: synthesized, cross-linked Markdown pages that people can read and edit, and agents can use as context.

**The engine is public. The data is private.** An instance keeps its pages, captures and configuration in a separate directory. The engines find it through `syntopica.config.json`; personal content stays outside the engine repositories.

**Start here:** hand [syntopica/syntopica](https://github.com/syntopica/syntopica) to your agent. Its `AGENTS.md` walks Claude Code or Codex through choosing components, installing them, verifying every engine and connecting itself.

- [brain](https://github.com/syntopica/brain) is the Python wiki engine: index, link graph, lint, doctor.
- [clips](https://github.com/syntopica/clips) is the capture and ingest engine: it turns saved web content into cited pages through a model, with validation and human diff approval.
- [atrium](https://github.com/syntopica/atrium) is retrieval over your own agent conversation history, served over MCP.
- [agents](https://github.com/syntopica/agents) is the agent control plane, and the conversation export atrium indexes.
- [clipper](https://github.com/syntopica/clipper) is the Chrome extension that clips pages into a GitHub inbox; [capture](https://github.com/syntopica/capture) is the phone URL inbox. Both need a fork and a deployment of your own.
- [test-data](https://github.com/syntopica/test-data) is a synthetic instance for exercising the engines; [codeality](https://github.com/syntopica/codeality) holds shared engineering standards.
