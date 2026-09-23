# Awesome-AI-Agent-Tool-Registry

## Top AI Agent Tool Registry Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Tool Registries for AI Agents, MCP Server Catalogs, Integration Hubs, Composable Agent Actions & Discoverable Tooling*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Tool Registries**. These systems catalog, host, and expose tools, APIs, and MCP servers so AI agents can discover and invoke external capabilities (email, CRM, code repos, databases, browsers, etc.) in a standardized way.



**Examples** include Composio, Pipedream Connect, Toolhouse, LangChain Hub, Smithery, Trigger.dev Integrations, Zapier MCP, Superface, OpenTools, and Apideck (the category leaders and adjacent integration platforms).



**Open-source emphasis**: The Model Context Protocol (MCP) and agent-tool ecosystems are highly open. Official and community MCP registries, **agentregistry**, **MCPfinder**, **OpenTool**, curated tool lists, and framework hubs (LangChain, etc.) provide strong open alternatives. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Composio](https://composio.dev/)**  

  Platform for connecting AI agents to tools and APIs with managed authentication, a large tool catalog, and strong support for agent frameworks and MCP.



- **[Smithery](https://smithery.ai/)**  

  MCP-focused registry and hosting platform for discovering, running, and managing Model Context Protocol servers.



- **[Pipedream Connect, Zapier MCP, Trigger.dev Integrations](https://pipedream.com/)**  

  Automation and integration platforms exposing large catalogs of app actions as tools or MCP servers for agents.



- **[Toolhouse, OpenTools, Superface, Apideck](https://www.toolhouse.ai/)**  

  Tool and API integration layers that help agents call external services with consistent interfaces and managed auth.



- **[LangChain Hub](https://smith.langchain.com/)**  

  Hub for sharing prompts, chains, and tools within the LangChain ecosystem—widely used for discoverable agent building blocks.



- **[Other commercial agent tool & integration platforms](https://composio.dev/)**  

  Solutions focused on tool registries, MCP hosting, and enterprise-ready agent integrations.



## Open-Source GitHub Projects



- **[Official Model Context Protocol registries & servers](https://github.com/modelcontextprotocol)**  

  Official MCP specification, SDKs, and the growing ecosystem of open MCP servers that form the backbone of many tool registries.



- **[agentregistry](https://github.com/agentregistry-dev/agentregistry)**  

  Open-source centralized registry for MCP servers, agents, skills, and prompts—with discovery, versioning, and one-command deployment for teams.



- **[MCPfinder](https://mcpfinder.dev/)**  

  Open-source discovery and install layer for MCP servers—aggregates multiple registries, scores trust signals, and generates install-ready configuration for AI clients.



- **[OpenTool](https://opentool.dev/)**  

  Open-source MCP server that aggregates authenticated access to many providers (GitHub, Notion, Slack, etc.) behind a single MCP endpoint with a clear tool registry model.



- **[Awesome AI Agent Tools & curated catalogs](https://github.com/michielhdoteth/awesome-ai-agent-tools)**  

  Large open collections of installable agent components—skills, MCP servers, workflows, subagents, hooks, and tools—with install commands and metadata.



- **[Community MCP server indexes](https://glama.ai/mcp/servers)**  

  Open catalogs (Glama, official registry mirrors, etc.) listing tens of thousands of community and official MCP servers across categories.



- **[LangChain / LlamaIndex / CrewAI tool ecosystems](https://github.com/langchain-ai/langchain)**  

  Open framework tool interfaces and community tool packages that act as de facto registries within each agent framework.



- **[Self-hosted tool gateway projects](https://github.com/search?q=MCP+gateway+OR+agent+tool+registry+open+source)**  

  Open gateways and registries that let organizations host private catalogs of approved tools for internal agents.



### Additional Strong Open-Source Options



- **MCP-native registries**: agentregistry, MCPfinder, and official/community MCP indexes as primary discovery layers.

- **Unified tool servers**: OpenTool-style projects that expose many providers through one MCP server.

- **Curated lists**: Awesome-style repositories for skills, MCP servers, and agent components.

- **Framework hubs**: LangChain Hub and equivalent open sharing mechanisms inside major agent frameworks.

- **Private registries**: Self-hosted catalogs for enterprise-approved tools only.

- Fully open stacks (MCP servers + open registry + open agent framework) are production-viable.



**Frameworks for building custom systems**:  

The open MCP ecosystem plus **agentregistry**, **MCPfinder**, **OpenTool**, and curated tool lists provide excellent foundations for agent tool discovery and execution.  

Commercial platforms (Composio, Smithery, Pipedream, Zapier, Toolhouse, etc.) add managed auth, enterprise governance, hosted reliability, and polished catalogs.  

Most teams combine open MCP servers and registries for flexibility with selective commercial tool platforms for critical SaaS integrations and support. Fully open registries and self-hosted MCP gateways work well when tool governance and data residency matter.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Giving AI agents access to tools and APIs creates security and data-exfiltration risk. Apply least-privilege credentials, review third-party tools, monitor tool use, and prefer private registries for sensitive environments.

- Open-source registries and MCP servers offer transparency and control but require you to manage hosting, updates, and trust evaluation. Commercial platforms shift operational burden to the provider. Validate security and compliance needs carefully.



---



**Made for AI engineers, agent developers, and platform teams building discoverable, governable tool ecosystems for agents.**  

Let's keep agent tooling open and interoperable—through thriving open MCP registries and complementary managed tool platforms.
