# MCP Servers and Tools I Use

This repository documents the Model Context Protocol (MCP) servers I frequently use and the tools they provide. MCP enables AI assistants like Claude to interact with external systems and data sources.

## MCP Servers

### 1. Desktop Commander

**Description:** A MCP server that gives Claude terminal control, file system search and diff file editing capabilities.

**Functionality:**
- Execute long-running terminal commands on your computer
- Manage processes through MCP
- Search and navigate file system
- Edit files with search and replace operations
- Run terminal commands with AI assistance

**Repository:** [https://github.com/wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP)

**Installation:** `npx -y @wonderwhy-er/desktop-commander`

### 2. Tavily MCP

**Description:** A MCP server that provides AI-powered web search and content extraction capabilities using Tavily's API.

**Functionality:**
- Perform comprehensive web searches
- Extract and process content from URLs
- Customize search parameters (depth, domains, time range, etc.)
- Filter and focus searches on specific content types
- Access news and general information searches

**Repository:** [https://github.com/tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp)

**Installation:** `npx -y tavily-mcp@0.1.4`

### 3. GitHub MCP

**Description:** GitHub's official MCP server that enables Claude to interact with GitHub repositories and features.

**Functionality:**
- Create, read, and update GitHub repositories
- Manage issues and pull requests
- Search code, repositories, users
- Review and comment on code
- Access and manipulate repository content
- Create branches and manage commits

**Repository:** [https://github.com/github/github-mcp-server](https://github.com/github/github-mcp-server)

**Installation:** Run via Docker with `docker run -i --rm -e GITHUB_PERSONAL_ACCESS_TOKEN ghcr.io/github/github-mcp-server`

### 4. Memory MCP

**Description:** A knowledge graph-based memory server that enables Claude to maintain contextual information and memory.

**Functionality:**
- Create and manage entities in a knowledge graph
- Establish relations between entities
- Add observations to existing entities
- Search for nodes in the knowledge graph
- Delete entities, relations, or observations
- Query and traverse the knowledge graph

**Repository:** [https://github.com/modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)

**Installation:** `npx -y @modelcontextprotocol/server-memory`

## Configuration

My current MCP server configuration is stored in `/home/joe/.config/Claude/claude_desktop_config.json`. This file contains connection details, API keys, and other settings for each MCP server.

## License

This documentation is for personal reference. All MCP servers mentioned maintain their own licenses as specified in their respective repositories.

---

**Last Updated:** April 2025

*Note: This is a personal tracking repository. For official documentation, please refer to the original repositories linked above.*
