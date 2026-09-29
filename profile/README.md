<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-inverse.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg">
  <img src="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg" alt="Syntopica" width="420">
</picture>

Coding agents are fast, but two things keep projects from getting anywhere: they forget everything between sessions, and they drift from the standards the code needs. Syntopica is the open-source tooling I use every day to fix both.

**The engine is public. The data is private.** An instance keeps its pages, captures and configuration in a separate directory. The engines find it through `syntopica.config.json`; personal content stays outside the engine repositories.

**Start here:** hand [syntopica/syntopica](https://github.com/syntopica/syntopica) to your agent. Its `AGENTS.md` walks Claude Code or Codex through choosing components, installing them, verifying every engine and connecting itself.

### Memory: agents that don't start from zero

- [brain](https://github.com/syntopica/brain) - a personal wiki an agent maintains and a person owns: synthesized, cross-linked Markdown pages, with index, link graph, lint and doctor.
- [atrium](https://github.com/syntopica/atrium) - retrieval over your own agent conversation history, served over MCP, so past decisions and fixes come back when they matter.
- [clips](https://github.com/syntopica/clips) - turns saved web content into cited wiki pages through a model, with validation and human diff approval.
- [clipper](https://github.com/syntopica/clipper) (Chrome extension) and [capture](https://github.com/syntopica/capture) (phone URL inbox) feed it. Both need a fork and a deployment of your own.

### Quality: code that holds up

- [agents](https://github.com/syntopica/agents) - the agent control plane: rules, skills and a workflow engine that enforce planning, testing and review across Claude Code, Codex and other IDEs.
- [codeality](https://github.com/syntopica/codeality) - shared engineering standards as installable packages (ESLint, Prettier, TypeScript) plus project templates, so agents have a bar they must pass.

[test-data](https://github.com/syntopica/test-data) is a synthetic instance for exercising the engines.
