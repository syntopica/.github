<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-inverse.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg">
  <img src="https://raw.githubusercontent.com/syntopica/brand/main/logos/svg/syntopica-horizontal-color.svg" alt="Syntopica" width="420">
</picture>

Syntopica is a personal wiki that an agent maintains and a person owns: synthesized, cross-linked Markdown pages that people can read and edit, and agents can use as context.

**The engine is public. The data is private.** An instance keeps its pages, captures and configuration in a separate directory. The engines find it through `syntopica.config.json`; personal content stays outside the engine repositories.

- [brain](https://github.com/syntopica/brain) is the Python wiki engine. It builds the page index and link graph, checks page conventions and diagnoses instance setup.
- [clips](https://github.com/syntopica/clips) is the TypeScript and Python capture and ingest engine. It triages saved web content and synthesizes wiki pages through a model, with validation and human diff approval before changes are accepted.
- [codeality](https://github.com/syntopica/codeality) holds shared engineering standards.
- [agents](https://github.com/syntopica/agents) is the agent control plane.

Three companion repositories are private: **clipper**, the Chrome extension for clipping pages; **capture**, the phone URL inbox; and **mem**, the conversation index.
