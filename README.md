# Quantum Metric for GitHub Copilot (CLI and VS Code)

Analyze funnels, errors, friction and session replays in Quantum Metric to find and fix digital experience issues.

## Install

**Copilot CLI**

```bash
copilot plugin marketplace add https://github.com/quantummetric/qm-plugin-copilot.git
copilot plugin install quantum-metric@quantum-metric
```

**VS Code:** add the server to your user `mcp.json` or `.vscode/mcp.json` and restart VS Code. A browser window opens for sign-in on first connect.

```json
{
  "servers": {
    "quantum-metric": {
      "type": "http",
      "url": "https://api.quantummetric.com/mcp"
    }
  }
}
```

## Configure

The server uses Quantum Metric sign-in (OAuth). Every call runs as you, with your role, permissions, workspace and timezone. No token is created or stored.

| Setting | Value |
|---|---|
| Endpoint | `https://api.quantummetric.com/mcp` |
| Subscription | Chosen when you sign in |

## Skills

- `getting-started`: confirms the subscription, workspace and timezone, and fixes common connection problems
- `data-analysis`: answers funnel, conversion, error and trend questions with verified numbers
- `session-review`: explains what a user experienced in one or more sessions

## Support

support@quantummetric.com, or the [Quantum Metric support portal](https://thequad.quantummetric.com/).

## Privacy

[Quantum Metric Privacy Policy](https://www.quantummetric.com/legal/privacy-policy)

## Terms

[Quantum Metric Terms and Conditions](https://iam.quantummetric.com/terms-and-conditions)

## License

MIT
