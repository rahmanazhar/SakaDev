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
- OpenRouter
- Anthropic
- OpenAI
- Google Gemini
- AWS Bedrock
- Azure
- GCP Vertex
- Local models via LM Studio/Ollama
- Token usage and cost tracking

### 🖥️ Terminal Integration
- Direct command execution
- Real-time output monitoring
- Background process support
- Environment-aware operations

### 📝 File Management
- Direct file creation and editing
- Diff view for changes
- Real-time error monitoring
- Timeline tracking for modifications

### 🌐 Browser Interaction
- Launch and control browsers
- Element interaction (clicks, typing, scrolling)
- Screenshot capture
- Console log monitoring
- Visual bug fixing
- Runtime issue debugging

### 🛠️ Extensible Tools
Using the [Model Context Protocol](https://github.com/modelcontextprotocol), SakaDev can create custom tools for:
- Jira ticket management
- AWS infrastructure control
- PagerDuty incident handling
- And more based on your needs

### 📚 Context Management
- **@url**: Import documentation from URLs
- **@problems**: Add workspace issues for fixing
- **@file**: Include specific file contents
- **@folder**: Import entire folder contents

## Development

### Contributing
Check our [open issues](https://github.com/rahmanazhar/SakaDev/issues) or [feature request board](https://github.com/rahmanazhar/SakaDev/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop) to get started.

## License
[Apache 2.0 © 2024 SakaDev by Hiroshi Aki.](./LICENSE)
