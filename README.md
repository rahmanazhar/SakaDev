# SakaDev - AI Pair Programming Assistant

<div align="center">
<table>
<tbody>
<td align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=rahmanazhar.saka-dev"><strong>VS Code Marketplace</strong></a>
</td>
<td align="center">
<a href="https://github.com/rahmanazhar/SakaDev/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop"><strong>Request Features</strong></a>
</td>
</tbody>
</table>
</div>

SakaDev is a powerful AI assistant that integrates directly with your development environment, leveraging [Claude 3.5 Sonnet's agentic capabilities](https://www-cdn.anthropic.com/fed9cc193a14b84131812372d8d5857f8f304c52/Model_Card_Claude_3_Addendum.pdf) to handle complex software development tasks with precision and intelligence.

## Key Features

### 🤖 Intelligent Project Understanding
- Analyzes file structures and source code ASTs
- Performs smart regex searches
- Reads and understands relevant files
- Manages context efficiently for large projects

### 💻 Development Capabilities
- Creates and edits files with real-time error monitoring
- Executes terminal commands with output tracking
- Launches and interacts with browsers for testing
- Fixes runtime errors and visual bugs autonomously

### 🔧 Workflow Integration
1. Input your task and attach relevant images
2. SakaDev analyzes your project context
3. Executes necessary actions (file edits, commands, testing)
4. Presents results with executable commands

> [!TIP]
> Use `CMD/CTRL + Shift + P` and search for "SakaDev: Open In New Tab" to work with SakaDev alongside your file explorer.

## Features in Detail

### 🌐 API Provider Support
- OpenRouter with provider sorting (throughput, price, latency)
- Anthropic with Claude 3.7 Sonnet
- OpenAI with GPT-4.5 preview
- Google Gemini with 2.5 Pro models
- AWS Bedrock with Nova models
- Azure OpenAI
- GCP Vertex AI
- DeepSeek with R1/V3 models
- Mistral AI
- xAI's Grok models
- Local models via LM Studio/Ollama/LiteLLM
- Comprehensive cost tracking and billing history

### 🖥️ Terminal Integration
- Direct command execution with auto-approval options
- Real-time output monitoring
- Background process support
- Environment-aware operations
- Quick access via 'Add to SakaDev' context menu
- Drag and drop file/folder support

### 📝 File Management
- Direct file creation and editing
- Diff view for changes with reliable search/replace
- Real-time error monitoring and auto-fixing
- Automatic checkpoints for workspace state
- Visual change indicators and restore options
- .sakadevignore support for file access control

### 🌐 Browser Interaction
- Launch and control browsers (Chrome or Chromium)
- Element interaction (clicks, typing, scrolling)
- Screenshot capture and console monitoring
- Visual bug fixing and runtime debugging
- Configurable viewport size and headless mode
- Session-based browsing with Chrome remote debugging

### 🛠️ Extensible Tools
Using the [Model Context Protocol](https://github.com/modelcontextprotocol), SakaDev can create custom tools for:
- Jira ticket management
- AWS infrastructure control
- PagerDuty incident handling
- And more via MCP Marketplace
- Individual tool auto-approval options
- Rich responses with image previews

### 📚 Context Management
- **@url**: Import documentation from URLs
- **@problems**: Add workspace issues for fixing
- **@file**: Include specific file contents
- **@folder**: Import entire folder contents
- **@terminal**: Reference active terminal contents
- **@git**: Access current changes or specific commits
- Plan/Act mode toggle for task planning
- Language preference settings

## Development

### Contributing
Check our [open issues](https://github.com/rahmanazhar/SakaDev/issues) or [feature request board](https://github.com/rahmanazhar/SakaDev/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop) to get started.

### Local Setup
<details>
<summary>Setup Instructions</summary>

1. Clone the repository (requires [git-lfs](https://git-lfs.com/)):
   ```bash
   git clone https://github.com/rahmanazhar/SakaDev.git
   ```

2. Open in VSCode:
   ```bash
   code sakadev
   ```

3. Install dependencies:
   ```bash
   npm run install:all
   ```

4. Launch with `F5` or `Run -> Start Debugging`

Note: You may need the [esbuild problem matchers extension](https://marketplace.visualstudio.com/items?itemName=connor4312.esbuild-problem-matchers) for building.
</details>

## License
[Apache 2.0 © 2024 SakaDev by Rahman Azhar.](./LICENSE)
