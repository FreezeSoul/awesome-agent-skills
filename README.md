# Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of useful resources for **Agent Skills** - a lightweight, open format for extending AI agent capabilities with specialized knowledge and workflows.

## 🌟 What are Agent Skills?

A **Skill** is a directory containing a `SKILL.md` file (with metadata and instructions) and optional scripts/resources. This format allows agents to discover and load capabilities on demand, a concept known as **"progressive disclosure"**.

Think of skills as "plugins" or "knowledge packs" that your agent can read to learn how to perform specific tasks—like editing a PDF, analyzing data, or managing a project—without needing that knowledge hardcoded into its system prompt.

[👉 Learn more at agentskills.io](https://agentskills.io)

## 📖 Contents

- [🧩 Skill Collections](#-skill-collections)
- [🛠️ Tools & Ecosystem](#-tools--ecosystem)
- [📚 Essential Reading](#-essential-reading)
- [📺 Videos](#-videos)
- [🔬 Research & Papers](#-research--papers)
- [💬 Join the Community](#-join-the-community)
- [🤝 How to Contribute](#-how-to-contribute)

## 🧩 Skill Collections

Ready-to-use skills to supercharge your agents.

- [anthropics/skills](https://github.com/anthropics/skills) - 🏆 **Official** collection from Anthropic (document editing, data analysis, etc.).
- [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills) - 50+ verified skills for Claude Code and Claude.ai.
- [shajith003/awesome-claude-skills](https://github.com/shajith003/awesome-claude-skills) - Skills to enhance capabilities in specialized areas.
- [ponderous-dustiness314/awesome-claude-skills](https://github.com/ponderous-dustiness314/awesome-claude-skills) - Essential skills for document editing, data analysis, and project management.
- [jacintarefined358/awesome-claude-skills](https://github.com/jacintarefined358/awesome-claude-skills) - Verified skills for productivity.
- [lifegenieai/claude-skills](https://github.com/lifegenieai/claude-skills) - Skills for voice AI, image generation, and web dev.
- [hikanner/agent-skills](https://github.com/hikanner/agent-skills) - Curated collection of Claude Agent Skills.
- [GuDaStudio/skills](https://github.com/GuDaStudio/skills) - Skills for collaboration between Claude and other agents.
- [bencium/bencium-claude-code-design-skill](https://github.com/bencium/bencium-claude-code-design-skill) - Comprehensive UX Designer skill.
- [Johnny2x2/Agent-Skills](https://github.com/Johnny2x2/Agent-Skills) - A library of Anthropic Agent Skills.
- [dennytosp/nextjs-claude-design-skill](https://github.com/dennytosp/nextjs-claude-design-skill) - Next.js UX Designer skill.
- [jakedahn/pomodoro](https://github.com/jakedahn/pomodoro) - Reference implementation of the 'System Skill Pattern' (CLI + SKILL.md + Database).
- [Thomas-TyTech/browser-skill](https://github.com/Thomas-TyTech/browser-skill) - Token-efficient `SKILL.md` bundle for controlling Chrome.
- [fabioc-aloha/spotify-skill](https://github.com/fabioc-aloha/spotify-skill) - 🎵 Spotify API integration skill.
- [kylehughes/the-unofficial-swift-concurrency-migration-skill](https://github.com/kylehughes/the-unofficial-swift-concurrency-migration-skill) - Swift Concurrency Migration Guide as a Skill.
- [gmickel/sheets-cli](https://github.com/gmickel/sheets-cli) - 📊 Google Sheets CLI with Agent Skills.
- [tubone24/midi-agent-skill](https://github.com/tubone24/midi-agent-skill) - 🎹 Generate MIDI files from text.
- [SawyerHood/dev-browser](https://github.com/SawyerHood/dev-browser) - 🌐 Give your agent a web browser.
- [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) - Skills for context engineering.
- [gotalab/skillport](https://github.com/gotalab/skillport) - Bring Agent Skills to any AI Agent via CLI or MCP.
- [formulahendry/agent-skill-code-runner](https://github.com/formulahendry/agent-skill-code-runner) - Run code snippets in multiple languages.
- [DiscreteTom/agent-skills-mcp](https://github.com/DiscreteTom/agent-skills-mcp) - Load Agent Skills using MCP.
- [OmidZamani/dspy-skills](https://github.com/OmidZamani/dspy-skills) - Claude Skills for DSPy framework.
- [gradion-ai/freeact-skills](https://github.com/gradion-ai/freeact-skills) - Predefined skills for the freeact agent library.
- [DougTrajano/pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) - Pydantic AI with Agent Skills.

## 🛠️ Tools & Ecosystem

Platforms and tools that support the Agent Skills specification.

- [OpenCode](https://opencode.ai/) - AI development tool supporting Agent Skills.
- [Cursor](https://cursor.com/) - AI code editor supporting Agent Skills.
- [Amp](https://ampcode.com/) - AI coding assistant.
- [Letta](https://www.letta.com/) - Platform for building stateful LLM agents.
- [Goose](https://block.github.io/goose/) - Open source AI agent.
- [Claude Code](https://claude.ai/code) - Anthropic's coding tool with native support.
- [openskills](https://github.com/numman-ali/openskills) - Universal skills loader for AI coding agents.
- [vibe-tools](https://github.com/eastlondoner/vibe-tools) - Give Cursor Agent an AI Team and Advanced Skills.
- [IntentKit](https://github.com/crestalnetwork/intentkit) - Framework for AI agents equipped with powerful skills.
- [Agentica](https://github.com/wrtnlabs/agentica) - TypeScript AI Function Calling Framework.
- [gemini-cli-skillz](https://github.com/intellectronica/gemini-cli-skillz) - Gemini CLI extension enabling Anthropic-style Agent Skills.
- [devskills](https://github.com/mk0e/devskills) - MCP server to bring Agent Skills to any MCP-compatible coding agent.
- [baml-anthropic-skills-integration](https://github.com/snedea/baml-anthropic-skills-integration) - Integration between BAML and Anthropic Agent Skills.
- [agentskills-mcp](https://github.com/zouyingcao/agentskills-mcp) - MCP server implementation for Agent Skills.
- [cc-wf-studio](https://github.com/breaking-brake/cc-wf-studio) - Workflow studio for ClaudeCode with skill support.
- [skillcheck](https://github.com/agentigy/skillcheck) - Security scanner for `SKILL.md` files.
- [cognitive-toolworks](https://github.com/williamzujkowski/cognitive-toolworks) - Generates agent artifacts like `SKILL.md` using LLM.
- [skill-optimization](https://github.com/instavm/skill-optimization) - DSPy optimization techniques for `SKILL.md` files.
- [AI-anything](https://github.com/yfe404/AI-anything) - Transforms YouTube videos into `SKILL.md` files.
- [system-skills-pattern-template](https://github.com/m3lander/system-skills-pattern-template) - Template for building System Skills (CLI + SKILL.md + Database).

## 📚 Essential Reading

- [Equipping agents for the real world with Agent Skills](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Anthropic Engineering Blog.
- [What are skills?](https://support.claude.com/en/articles/12512176-what-are-skills) - Claude Support.
- [Using skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - Guide on using skills.
- [How to create custom skills](https://support.claude.com/en/articles/12512198-creating-custom-skills) - Guide on authoring skills.
- [Skills API Quickstart](https://docs.claude.com/en/api/skills-guide#creating-a-skill) - Technical documentation.
- [Stream Coding Methodology](https://github.com/frmoretto/stream-coding) - Documentation-first methodology including official `SKILL.md` for Claude/Cursor.

## 📺 Videos

*Note: As this is a new standard, video content is emerging. Check back soon for tutorials and demos!*

- [Anthropic Agent Skills Announcement](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - (Blog post with embedded concepts).

## 🔬 Research & Papers

Academic research related to Agent Skills and progressive disclosure.

- [A survey of agent interoperability protocols](https://arxiv.org/abs/2505.02279) (2025) - Discusses protocols like MCP and 'Agent Cards'.
- [The Effect of Progressive Disclosure in the Transparency of Large Language Models](https://link.springer.com/chapter/10.1007/978-3-031-82633-7_17) (2024) - Research on progressive disclosure.
- [Disclosures & disclaimers: Investigating the impact of transparency disclosures](https://ojs.aaai.org/index.php/HCOMP/article/view/31597) (2024) - Investigates transparency disclosures.

## 💬 Join the Community

- [Agent Skills GitHub Discussions](https://github.com/agentskills/agentskills/discussions) - Official specification discussions.
- [Anthropic Skills GitHub Issues](https://github.com/anthropics/skills/issues) - Issues for example skills.

## 🤝 How to Contribute

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
