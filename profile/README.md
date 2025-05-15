# 👋 Welcome to tip.md

<div align="center">
  <a href="https://tip.md/tipdotmd">
    <img src="https://tip.md/badge.svg" alt="Tip in Crypto" width="150">
  </a>
  <h3>The crypto bridge for open-source rewards</h3>
  <p>A simple way to receive cryptocurrency tips through your GitHub README</p>
</div>

## 🚀 What is tip.md?

tip.md makes it easy for developers to receive cryptocurrency tips through a simple button embedded in their GitHub READMEs or any markdown-supported platform. Get rewarded for your open source work in minutes!

## ✨ How It Works

### For Developers or Projects:

1. **Connect GitHub or register via email**
   Sign in to [tip.md](https://tip.md) and save your crypto wallet addresses in your dashboard.

2. **Add your tipping button**
   Copy the markdown snippet and paste it into your GitHub README file. No code changes required!

3. **Receive tips**
   When someone appreciates your work, they can send you tips in cryptocurrency directly through your README button.

### For Supporters:

1. **Find a developer with a tip.md button**
   Look for the [![Tip in Crypto](https://tip.md/badge.svg)](https://tip.md/tipdotmd) button in GitHub READMEs.

2. **Click the button**
   This takes you to the developer's tipping page where you can show your appreciation.

3. **Send a tip in your preferred cryptocurrency**
   Support open source contributors directly with crypto.

## 💰 Supported Cryptocurrencies

- **Ethereum** - The leading smart contract platform with widespread adoption.
- **Solana** - Fast, low-cost blockchain for those that want speed and minimal transaction fees.
- **Bitcoin Lightning** - Instant Bitcoin payments with minimal fees using the Lightning Network.

## 🔗 Add a Tip Button to Your GitHub README

Simply add this markdown to your README file:

```markdown
[![Tip in Crypto](https://tip.md/badge.svg)](https://tip.md/YOUR_USERNAME)
```

Replace `YOUR_USERNAME` with your tip.md username.

## 🤖 MCP Server for AI Assistants

tip.md offers an MCP (Model Context Protocol) server that allows AI assistants like Claude and Cursor to interact with tip.md's crypto tipping functionality directly.

### Integration Options:

- **Cursor**: Add our service to `~/.cursor/mcp.json`:
  ```json
  {
    "mcpServers": {
      "tip.md": {
        "command": "npx mcp-remote https://mcp.tip.md/mcp"
      }
    }
  }
  ```

- **Sage App**: Add as a Streamable HTTP server with endpoint URL: `https://mcp.tip.md/mcp`

- **Claude Desktop**: Use with Supergateway to bridge HTTP-stream to stdio

For detailed setup instructions, visit our [Documentation](https://tip.md/documentation?tab=mcp-server).

## 🌟 Benefits

- **Multi-blockchain support** - Accept tips in Ethereum, Solana, and Bitcoin (using Lightning).
- **Simple integration** - Just add a markdown snippet to your repo README file or any other markdown-supported platform.
- **Low fees** - Sustainable 4% fee powers our infrastructure and development - the rest is all yours.
- **No code changes** - No need to modify your application code or implement complex payment systems.
- **AI integration** - Connect your AI assistants to enable crypto tipping capabilities through our MCP service.

## 🔍 Examples

Here's how the tip.md button looks in a README:

[![Tip in Crypto](https://tip.md/badge.svg)](https://tip.md/tipdotmd)

## 🔗 Useful Links

- [Website](https://tip.md)
- [Dashboard](https://tip.md/dashboard)
- [Documentation](https://tip.md/documentation)
- [Support](mailto:support@tip.md)
- [Join our discussion](https://github.com/orgs/tipdotmd/discussions/1)

## 📄 License

All rights reserved. The tip.md service is provided as-is.

---

<div align="center">
  <p>Ready for your open source work to be recognized and supported?</p>
  <p><a href="https://tip.md/auth">Get Started for Free</a></p>
</div>
