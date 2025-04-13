# mcp-console-application

- An MCP server created from the [quick start guide](https://modelcontextprotocol.io/quickstart/server) in the [MCP documentation](https://modelcontextprotocol.io/introduction)
- An MCP client created from the [quick start guide](https://modelcontextprotocol.io/quickstart/server) in the [MCP documentation](https://modelcontextprotocol.io/introduction)
- A monorepo build process to build and start them together

## Requirements

Anthropic API KEY in a .env

```
ANTHROPIC_API_KEY=<YourApiKey>
```

## Setup

- Clone repo
- Create .env with your Anthropic API Key
- `npm install`
- `npm run build`
- `npm run start`

## Purpose

- Demonstrate ability to read, understand, and follow directions from documentation
- Demonstrate general proficiency with typescript and npm
- Explore possibilities of Model Context Protocol

## Notes

- Check the package.json to see how to build each package independently
- The server can be used in any client that supports MCP Clients (Claude)
