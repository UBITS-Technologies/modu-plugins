# Modu plugins for Claude Code and Codex

[Modu](https://modu.ubits.tech) runs Discord servers, Slack workspaces and WhatsApp numbers. With this plugin your agent reads the server, plans the change and sends the plan to Modu. Modu checks every step against your plan and the platform's rules, does the work, and waits for your approval before anything destructive. Plans your agent makes use no Modu AI credits.

The plugin adds:

- the `modu` MCP server (`https://modu.ubits.tech/mcp/all`): Discord setup and plans, the ticket queue, Slack workspaces and WhatsApp numbers linked to your Modu plan;
- a `modu` skill that tells the agent how to plan with Modu safely.

You need a Modu account. Sign-in happens in your browser the first time the agent uses Modu; you choose what it may do.

## Claude Code

```
/plugin marketplace add UBITS-Technologies/modu-plugins
/plugin install modu@modu
```

Then type `/mcp`, pick `plugin:modu:modu` and choose **Authenticate** to sign in to Modu.

From a shell: `claude plugin marketplace add UBITS-Technologies/modu-plugins && claude plugin install modu@modu`.

## Codex

```
codex plugin marketplace add UBITS-Technologies/modu-plugins
codex plugin add modu@modu
```

Then sign in to Modu in your browser:

```
codex mcp login modu
```

## Claude (web, desktop and mobile)

No plugin needed: [add Modu to Claude](https://modu.ubits.tech/go/claude) opens Claude's "Add custom connector" with Modu filled in.

## More

- All clients and options (Cursor, VS Code, ChatGPT, personal access tokens): https://modu.ubits.tech/connect-ai
- Privacy: https://modu.ubits.tech/privacy · Terms: https://modu.ubits.tech/terms

© UBITS LIMITED. Plugin files under the MIT licence; the Modu service is covered by its own terms.
