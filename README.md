# GitHub Copilot CLI (Community Edition)

The power of GitHub Copilot, now in your terminal.

This is a community edition CLI tool for GitHub Copilot. This repository provides a basic CLI setup that can be installed globally.

> **Note:** This is a community project. For the official GitHub Copilot CLI with full features, please visit [GitHub's official Copilot CLI documentation](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) and install `@github/copilot`.

## 📦 Installation and Usage

### Prerequisites

- **Node.js** v14 or higher
- **npm** v6 or higher

### Installation Options

#### Option 1: Install from Source (This Repository)

1. Clone this repository:
```bash
git clone https://github.com/teefisher2k20/copilot-cli.git
cd copilot-cli
```

2. Install globally:
```bash
npm install -g .
```

Or use npm link for development:
```bash
npm link
```

3. Run the CLI:
```bash
copilot-cli
```

#### Option 2: Install Official GitHub Copilot CLI

For the full-featured official GitHub Copilot CLI:
```bash
npm install -g @github/copilot
```

### Usage

After installation, you can run the CLI from anywhere:

```bash
# Run the CLI
copilot-cli

# Show help
copilot-cli --help

# Show version
copilot-cli --version
```

### Running in VS Code

To use this CLI in VS Code:

1. Open the integrated terminal in VS Code (`Ctrl+` ` or `Cmd+` `)
2. Run `copilot-cli` in the terminal
3. The CLI will execute in your current workspace directory

You can also:
- Add it as a task in `.vscode/tasks.json`
- Create a keyboard shortcut to run it
- Use it in your npm scripts in `package.json`

### For Official GitHub Copilot CLI Features

For full features including:
- Terminal-native AI-powered coding assistance
- GitHub integration (repositories, issues, PRs)
- Agentic capabilities (build, edit, debug, refactor)
- MCP-powered extensibility
- Multiple AI models (Claude Sonnet, GPT-5, etc.)

Please install the official GitHub Copilot CLI:
```bash
npm install -g @github/copilot
```

**Requirements for Official CLI:**
- Node.js v22 or higher
- npm v10 or higher
- Active Copilot subscription
- See [official documentation](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)

## 🛠️ Development

To contribute or modify this CLI:

1. Clone the repository
2. Make your changes
3. Test locally with `npm link`
4. Submit a pull request

## 📄 License

See [LICENSE.md](LICENSE.md) for details.
